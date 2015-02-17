
# ext-theme-oep
=============

ExtJS theme for Open ePlatform and Open eMap. Based on Ext JS 4.

## Source code
The source code is created in the [SASS filestructure](http://sass-lang.com/), and built to ordinary css-files and images. The builds are put in the build catalog.

## Usage



Use theme in ExtJS applications using the following snippet:

```html
    <link rel="stylesheet" type="text/css" href="ext-theme-oep/build/resources/osynlig-oep-theme-all.css">
```

Make sure the images catalog is placed at the same location as osynlig-oep-theme-all.css

## Build



1. Download and extract ExtJS v 4.x.x
    * http://www.sencha.com/products/extjs/download/ext-js-4.2.1
2. Download and install Sencha CMD Tools 4.x.x
    * http://www.sencha.com/products/sencha-cmd/download
4. Clone or download ` https://github.com/Sundsvallskommun/ext-theme-oep ` into the  packages folder in the extracted ExtJS folder
5. Open the terminal cd into the theme folder ` packages/ext-theme-oep `
6. Run ` sencha package upgrade ` command to upgrade package
7. Run ` sencha package build ` command to build theme
8. CSS and image files will be created in the ` build/resources ` folder.