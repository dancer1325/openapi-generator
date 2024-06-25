# Types of configuration options
* [global properties](./global-properties.md)
* config options
  * 👁️ specific to each individual [generator](./generators/README.md) 👁️
    * can be validated / generator
  * CLI -- via "additional properties" -- accepts them (❓)
* additional properties
  * := those / passed to -- templates
  * uses
    * user-defined properties
    * some config options
      * **Note:** 👁HOWEVER generators will read/modify/rewrite config options 👁
    * within templates
      * _Example:_ custom `generatedBy` key / value of `Jim Schubert` for inclusion in a custom CVS-like header
* top-level properties
  * specific to individual tools/plugins
  * uses
    * bootstrap our tooling

* TODO:

## Discovering options
* depends on type
  * global properties
    * Check '../global-properties.md'
  * config options
    * Check generator's documentation
    * `openapi-generator config-help -g generatorName` 
      * == via CLI
      * _Example:_ `openapi-generator config-help -g spring`
  * top-level properties
    * TODO:
  