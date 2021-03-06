## ngx translate merge [![Build Status](https://travis-ci.com/realappie/ngx-translate-merge.svg?branch=master)](https://travis-ci.com/realappie/ngx-translate-merge)

This CLI tool will merge your translation files based on one master file,

### Usage


```bash
ngx-translate-merge
```

You will need a `ngx-translate-merge.json` in the root directory that looks a bit like this

```json
{
    "i18nFilesPath": "i18n",
    "masterFileName": "en.json",
    "addMissing": true,
    "overwrite": false,
    "removeRedundant": false
}
```

Flags

```
Usage: node ngx-translate-tool [options]

Options:
  --[no]addMissing: Adds missing translation keys
    (default: false)
  --[no]removeRedundant: Removes redundant translation keys
    (default: false)
  --[no]overwrite: Whether to overrwrite original files or not
    (default: false)
  --fileType: What type of translation files
    (default: "json")
```
