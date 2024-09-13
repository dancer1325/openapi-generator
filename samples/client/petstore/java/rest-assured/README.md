# petstore-rest-assured

## Requirements

* install [Maven](https://maven.apache.org/)

## Installation & Usage

* `mvn install` 
  * install the API client library | your local Maven repository
* `mvn deploy` 
  * deploy it | remote Maven repository
    * -> configure "settings.xml"
* if you want to use it -> add it | your "pom.xml"

    ```xml
    <dependency>
        <groupId>org.openapitools</groupId>
        <artifactId>petstore-rest-assured</artifactId>
        <version>1.0.0</version>
        <scope>compile</scope>
    </dependency>
    ```

## Recommendation

* create an instance of `ApiClient` / thread | multithreaded environment
  * Reason: 🧠avoid potential issues 🧠
