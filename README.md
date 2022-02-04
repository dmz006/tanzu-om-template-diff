# pivnet-product-config-diff

Tanzu Product Version Configuration Variable diff will provide a list of product tile configuration variable changes
between release versions

```
Usage:
       pivnet-product-config-diff [options]
Example:
       pivnet-product-config-diff -p "elastic-runtime" -r "2.10.25 2.10.23"

where [options] are:
  -p, --product=<s>           Product Slug List
  -r, --releases=<s>          Releases to diff
  -d, --dont-clean-folders    Don't Clean Temp Folder
  -v, --version               Print version and exit
  -h, --help                  Show this message
```

# To Install
git clone https://github.com/dmz006/tanzu-om-template-diff.git

bundle
