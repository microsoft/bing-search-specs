## Node.js

These settings apply only when `--nodejs` is specified on the command line.
Please also specify `--node-sdks-folder=<path to root folder of your microsoft-sdk-for-node clone>`.

``` yaml $(nodejs)
nodejs:
  package-name: microsoft-bing-autosuggest
  output-folder: $(node-sdks-folder)/lib/services/BingAutoSuggest
  azure-arm: false
  generate-license-txt: true
  generate-package-json: true
  generate-readme-md: false
```
