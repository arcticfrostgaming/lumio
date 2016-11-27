<p align="center"><img src="https://cdn.rawgit.com/arcticicestudio/lumio/develop/src/assets/lumio-logo-banner.svg"/></p>

<p align="center"><img src="https://cdn.travis-ci.org/images/favicon-c566132d45ab1a9bcae64d8d90e4378a.svg" width=24 height=24/> <a href="https://travis-ci.org/arcticicestudio/lumio"><img src="https://img.shields.io/travis/arcticicestudio/lumio/develop.svg"/></a> <img src="https://circleci.com/favicon.ico" width=24 height=24/> <a href="https://circleci.com/gh/arcticicestudio/lumio"><img src="https://circleci.com/gh/arcticicestudio/lumio.svg?style=shield&circle-token=2c4d949a6e02d4e08bf2e1d1a42b4e46beefb93e"/></a> <img src="https://assets-cdn.github.com/favicon.ico" width=24 height=24/> <a href="https://github.com/arcticicestudio/lumio/releases/latest"><img src="https://img.shields.io/github/release/arcticicestudio/lumio.svg"/></a> <a href="https://github.com/arcticicestudio/lumio/releases/latest"><img src="https://img.shields.io/badge/pre--release---_-blue.svg"/></a> <img src="https://www.npmjs.com/static/images/touch-icons/favicon-32x32.png" width=24 height=24/> <a href="https://www.npmjs.com/package/lumio"><img src="https://img.shields.io/npm/v/lumio.svg"/></a> <a href="https://www.npmjs.com/package/lumio"><img src="https://img.shields.io/npm/dt/lumio.svg"/></a> <a href="https://www.npmjs.com/package/lumio"><img src="https://img.shields.io/npm/dm/lumio.svg"/></a></p>

<p align="center">A luminous warm and calm color palette.</p>

<p align="center">Created for the steam- and comic-like flat design pattern to achieve a optimal unobtrusive feeling for game- and graphic projects.<br>
It consists of a total of eighty one, carefully selected, dimmed pastel colors for a eye-comfortable, but yet colorful ambiance.</p>

---

The color palette it divided into fifteen named components to represent the different color effects.

![Lumio Palette Overview](https://cdn.rawgit.com/arcticicestudio/lumio/develop/src/assets/lumio-overview.svg)

Lumio colors are numbered from `lumio0` to `lumio15` where each component contains a different amount of colors:  
  1. **Rough Coal** `lumio0` - `lumio4`
  2. **Soft Earth** `lumio5` - `lumio13`
  3. **Hard Metal** `lumio14` - `lumio17`
  4. **Piquant Olive** `lumio18` - `lumio21`
  5. **Cold Snow** `lumio22` - `lumio25`
  6. **Clear Water** `lumio26` - `lumio34`
  7. **Hot Flame** `lumio35` - `lumio40`
  8. **Roasted Cocoa Bean** `lumio41` - `lumio46`
  9. **Tropical Wood** `lumio47` - `lumio51`
  10. **Fine Sand** `lumio52` - `lumio56`
  11. **Sweet Banana** `lumio57` - `lumio60`
  12. **Calm Sunset** `lumio61` - `lumio65`
  13. **Living Forest** `lumio66` - `lumio70`
  14. **Deep Sea** `lumio71` - `lumio75`
  15. **Fresh Wild Berries** `lumio76` - `lumio80`

## Usage
To show a list of all available [Gulp][gulp] tasks run `gulp` or `gulp help`.

### CSS
The [CSS specification](https://www.w3.org/TR/css-variables) supports the usage of primitive value types to define custom properties which can be used to create e.g. color variables.  
Lumio provides the `template-css.scss` template file to compile a `lumio.css` stylesheet.

The generated file contains all Lumio color variables prefixed with `--` inside the `:root` pseudo-class.  
The `:root` pseudo-class represents an element that is the root of the document.  
This is always the HTML (`<html>`) element which allows to use the Lumio color variables for the whole document.

The `lumio.css` stylesheet can be compiled via [Gulp][gulp]:  
```sh
npm install
gulp compile-css-template
```

### <img src="http://sass-lang.com/favicon.ico" width=16 height=16 /> Sass
Copy the `lumio.scss` file into your project and import it in your [Sass](http://sass-lang.com) files:
```css
@import "lumio";
```
The `.scss` file extension is optional.

#### <img src="http://sassdoc.com/favicon.png" width=16 height=16 /> SassDoc
lumio Sass sources are documented using the [SassDoc](http://sassdoc.com) documentation syntax which can be compiled to a HTML documentation via [Gulp][gulp]:  
```sh
npm install
gulp sassdoc
```
The Sassdoc theme can be changed by editing the `.sassdocrc` configuration file.

### <img src="http://lesscss.org/public/ico/favicon.ico" width=16 height=16/> LESSCSS
Copy the `lumio.less` file into your project and import it in your [LESSCSS](http://lesscss.org) files:  
```css
@import "lumio";
```
Information about how the `@import` statement handles imports with different file extensions can be found in the [official LESSCSS documentation](http://lesscss.org/features/#import-directives-feature).

#### KSS
lumio LESSCSS sources are documented using the [KSS](http://warpspire.com/kss) documentation syntax.  
Information about the generation of a styleguide can be found in the [official KSS documentation](http://warpspire.com/kss/styleguides).

### <img src="https://cdn.rawgit.com/arcticicestudio/lumio/develop/src/assets/icon-color-swatch.svg"/> Color Swatches
Lumio is available in various native formats:
  - `.aco` Adobe Photoshop Palette
  - `.ase` Adobe Swatch Exchange
  - `.gpa` Gpick Palette
  - `.gpl` GIMP/Inkscape/CinePaint/Krita Palette
  - `.mtl` Alias/WaveFront Material

A list of detailed information about each file format can be found [here](http://www.selapa.net/swatches/colors/fileformats.php).

## Port Projects
[![Lumio Java](https://cdn.rawgit.com/arcticicestudio/lumio/develop/src/assets/lumio-java-banner.svg)](https://github.com/arcticicestudio/lumio-java)

## Component Cards
<p align="center"><img src="https://cdn.rawgit.com/arcticicestudio/lumio/develop/src/assets/lumio-component-rough-coal.svg"/><img src="https://cdn.rawgit.com/arcticicestudio/lumio/develop/src/assets/lumio-component-soft-earth.svg"/><br><img src="https://cdn.rawgit.com/arcticicestudio/lumio/develop/src/assets/lumio-component-hard-metal.svg"/><img src="https://cdn.rawgit.com/arcticicestudio/lumio/develop/src/assets/lumio-component-piquant-olive.svg"/><br><img src="https://cdn.rawgit.com/arcticicestudio/lumio/develop/src/assets/lumio-component-cold-snow.svg"/><img src="https://cdn.rawgit.com/arcticicestudio/lumio/develop/src/assets/lumio-component-clear-water.svg"/><br><img src="https://cdn.rawgit.com/arcticicestudio/lumio/develop/src/assets/lumio-component-hot-flame.svg"/><img src="https://cdn.rawgit.com/arcticicestudio/lumio/develop/src/assets/lumio-component-roasted-cocoa-bean.svg"/><br><img src="https://cdn.rawgit.com/arcticicestudio/lumio/develop/src/assets/lumio-component-tropical-wood.svg"/><img src="https://cdn.rawgit.com/arcticicestudio/lumio/develop/src/assets/lumio-component-fine-sand.svg"/><br><img src="https://cdn.rawgit.com/arcticicestudio/lumio/develop/src/assets/lumio-component-sweet-banana.svg"/><img src="https://cdn.rawgit.com/arcticicestudio/lumio/develop/src/assets/lumio-component-calm-sunset.svg"/><br><img src="https://cdn.rawgit.com/arcticicestudio/lumio/develop/src/assets/lumio-component-living-forest.svg"/><img src="https://cdn.rawgit.com/arcticicestudio/lumio/develop/src/assets/lumio-component-deep-sea.svg"/><br><img src="https://cdn.rawgit.com/arcticicestudio/lumio/develop/src/assets/lumio-component-fresh-wild-berries.svg"/></p>

## Development
[![](https://img.shields.io/badge/Changelog-1.1.0-blue.svg)](https://github.com/arcticicestudio/lumio/blob/v1.1.0/CHANGELOG.md) [![](https://img.shields.io/badge/Workflow-gitflow_Branching_Model-blue.svg)](http://nvie.com/posts/a-successful-git-branching-model) [![](https://img.shields.io/badge/Versioning-ArcVer_0.8.0-blue.svg)](https://github.com/arcticicestudio/arcver)

### Contribution
Please report issues/bugs, feature requests and suggestions for improvements to the [issue tracker](https://github.com/arcticicestudio/lumio/issues).

<p align="center"> <img src="http://arcticicestudio.com/favicon.ico" width=16 height=16/> Copyright &copy; 2016 Arctic Ice Studio</p>

<p align="center"><a href="http://www.apache.org/licenses/LICENSE-2.0"><img src="https://img.shields.io/badge/License-Apache_2.0-blue.svg"/></a> <a href="https://creativecommons.org/licenses/by-sa/4.0"><img src="https://img.shields.io/badge/License-CC_BY--SA_4.0-blue.svg"/></a></p>

[gulp]: http://gulpjs.com
