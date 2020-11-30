## Ruby

These settings apply only when `--ruby` is specified on the command line.

``` yaml
package-name: microsoft_bing_spellcheck
package-version: "0.16.0"
azure-arm: true
```

### Ruby multi-api

``` yaml $(ruby) && $(multiapi)
batch:
  - tag: release_1_0
```

### Tag: release_1_0 and ruby

These settings apply only when `--tag=release_1_0 --ruby` is specified on the command line.
Please also specify `--ruby-sdks-folder=<path to the root directory of your microsoft-sdk-for-ruby clone>`.

``` yaml $(tag) == 'release_1_0' && $(ruby)
namespace: "Microsoft::Bing::SpellCheck::V1_0"
output-folder: $(ruby-sdks-folder)/data/microsoft_bing_spellcheck/lib
title: "SpellCheckClient"
```
