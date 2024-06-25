# Goal
* OpenAPI Generator commands
  * allowed via
    * CLI  -- Check '../cliInstallation' --
      * 👁️Used to display the next commands 👁️
      * ⚠️Based on installation -- it could be -- `openapi-generator-cli` or `openapi-generator` ⚠️
    * Maven / Gradle plugins
    * Online Generation 
    

## TODO:

## `... config-help`
* TODO:

## TODO:

## `... generate`
* `openapi-generator-cli generate -g generatorName -o outputDirectory -i inputOpenAPIDocument -otherOptionalOptions`
  * mandatory options
    * `-g`
    * `-o`
    * `-i`
  * `otherOptionalOptions`
    * `openapi-generator-cli help generate` to display ALL
  * `-Dcolor`
    * color terminal outputs
* allows
  * generating code -- via -- specified generator
* `.. --additional-properties=key1=value1,key2=value2,...`
  * allows
    * passing generator-specific options
  * _Examples:_
    * _Example1:_ `openapi-generator generate -g go --additional-properties=prependFormOrBodyParameters=true -o generateAdditionalProperty -i https://raw.githubusercontent.com/openapitools/openapi-generator/master/modules/openapi-generator/src/test/resources/3_0/petstore.yaml`
      * 'generateAdditionalProperty/' is the project generated
* TODO:
* _Examples_:
  * _Example1:_ `openapi-generator generate -g java -o generatesample -i https://raw.githubusercontent.com/openapitools/openapi-generator/master/modules/openapi-generator/src/test/resources/3_0/petstore.yaml`
    * 'generatesample' is the project generated
  * _Example:_ TODO:

# TODO:
