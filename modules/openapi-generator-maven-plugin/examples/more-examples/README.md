## Goal
* Comprehend `plugin.executions.*.configuration`
  * `verbose`
  * `inputSpec`
  * `inputSpecRootDirectory`

## How has it been created?
* `mvn archetype:generate -DgroupId=com.example -DartifactId=more-examples -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false`

## How to run?
* `mvn clean compile`
  * Problems
    * Problem1: "package javax.annotation does not exist"
      * Solution: Add 'javax.annotation:javax.annotation-api' dependency
    * Problem2: "package okhttp3.internal.http does not exist" & "package io.gsonfire does not exist"
      * Attempt1: Add the dependencies
      * Attempt2: Add `plugin.dependencies`
      * Solution: TODO:
