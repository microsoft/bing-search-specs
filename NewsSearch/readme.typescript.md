## TypeScript

These settings apply only when `--typescript` is specified on the command line.
Please also specify `--typescript-sdks-folder=<path to root folder of your microsoft-sdk-for-js clone>`.

``` yaml $(typescript)
typescript:
  package-name: "@microsoft/bing-newssearch"
  output-folder: "$(typescript-sdks-folder)/sdk/bing/bing-newssearch"
  azure-arm: false
  generate-metadata: true
```
