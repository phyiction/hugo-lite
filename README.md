# Hugo lite

## Description
A minimalist blog theme for Hugo built using the [Bulma](https://bulma.io/) 
CSS framework and icons from [Material Symbols](https://fonts.google.com/icons) 
and [Font Awesome](https://fontawesome.com/).

## Theme Parameters

`config.toml` or `hugo.toml`

```
...

[params]
  # See https://gohugo.io/functions/format/#layout-string for possible values
  dateFormat = "" # Defaults to "Jan 02, 2006" 
  timeFormat = "" # Defaults to "3:04 PM MST"

  # Image to display in navbar for brand
  logo = "" # Path to image

  [params.social]
    # See https://fontawesome.com/search?o=r&f=brands for valid keys
    github = "https://github.com/username"
    linkedin = "https://www.linkedin.com/in/username/"

...
```

## Installation

```
git submodule add --depth=1 https://github.com/phyiction/hugo-lite.git themes/lite
git submodule update --init --recursive
```

## Support

Create an issue on GitHub [here](https://github.com/phyiction/hugo-lite/issues/new). 