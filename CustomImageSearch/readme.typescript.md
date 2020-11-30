## TypeScript

These settings apply only when `--typescript` is specified on the command line.
Please also specify `--typescript-sdks-folder=<path to root folder of your microsoft-sdk-for-js clone>`.

``` yaml $(typescript)
typescript:
  package-name: "@microsoft/bing-customimagesearch"
  output-folder: "$(typescript-sdks-folder)/sdk/bing/bing-customimagesearch"
  azure-arm: false
  generate-metadata: true
```
