<p align="center"><img src="https://cdn.rawgit.com/arcticicestudio/lumio/develop/src/assets/lumio-logo-banner.svg"/></p>

<p align="center"><img src="https://assets-cdn.github.com/favicon.ico" width=24 height=24/> <a href="https://github.com/arcticicestudio/lumio/releases/latest"><img src="https://img.shields.io/github/release/arcticicestudio/lumio.svg"/></a> <img src="https://www.npmjs.com/static/images/touch-icons/favicon-32x32.png" width=24 height=24/> <a href="https://www.npmjs.com/package/lumio"><img src="https://img.shields.io/npm/v/lumio.svg"/></a> <a href="https://www.npmjs.com/package/lumio"><img src="https://img.shields.io/npm/dt/lumio.svg"/></a> <a href="https://www.npmjs.com/package/lumio"><img src="https://img.shields.io/npm/dm/lumio.svg"/></a></p>

---

# 2.0.0 (2016-11-37)
**The milestone [Version 2.0.0](https://github.com/arcticicestudio/lumio/milestone/1) release!**

The whole project has been rewritten and cleaned up to adapt to the new project setup like the [Nord](https://github.com/arcticicestudio/nord) project.

## Features
### Naming Scheme
**Color names**
The current naming scheme, where each color got an individual name based on the value, will be replaced with an numbered format.  
Example: `dark-livid-wood` will be renamed to `lumio0`, `sandrift` to `lumio17`.  
This will continue with a continuous numerating where the current position of a color represents its number.

![Lumio Dark Palette Overview](https://cdn.rawgit.com/arcticicestudio/lumio/develop/src/assets/lumio-overview.svg)

**Components**
Next to this, the color palette will be divided into fifteen named components to represent the different color effects where each component contains a different amount of colors:  
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

The X11 color scheme names and RGB value variables have been removed, but X11 color names are still included in the Sass- and LESSCSS source documentations.

### Source Formats
**Sass**
All [Sass](http://sass-lang.com) sources have been documented via [SassDoc](http://sassdoc.com) and a `template-css.scss` is available to be compiled to a CSS file including all color variables which is compatible to the CSS specification.  
The SassDoc is configurable via the `.sassdocrc` file.
(@arcticicestudio, #3, 706b639e)

**LESSCSS**
All [LESSCSS](http://lesscss.org) sources have been documented via [KSS](http://warpspire.com/kss).
(@arcticicestudio, #4, a7b2a57d)

**Native**
All native files have been recreated containing the new color and the new color naming scheme.
(@arcticicestudio, #5, 0b6ed117)
  
### Build Tools
**Gulp**
Introduced a [Gulp](gulpjs.com) file to compile Sass sources to CSS, provide a local hot-reload server for instant recompilatio on file changes and to build the new [SassDoc](http://sassdoc.com).  
(@arcticicestudio, #8, 2b39abfe)

**Travis CI and Circle CI**
Added the `.travis.yml` and `circle.yml` configuration files for continuous integration web services.
(@arcticicestudio, #6, d33ff382)

### NPM
A `package.json` file has been added to provide project meta data and dependencies for a release as a [NPM](http://npmjs.com) package.
(@arcticicestudio, #7, 2b39abfe)

### Assets
All project branding assets have been removed and replaced with new, modern SVG and AI files.
(@arcticicestudio, #2, 9edbcee1)

**Port Projects**  
[![Lumio Java](https://cdn.rawgit.com/arcticicestudio/lumio/develop/src/assets/lumio-java-banner.svg)](https://github.com/arcticicestudio/lumio-java)

**Component Cards**  
<p align="center"><img src="https://cdn.rawgit.com/arcticicestudio/lumio/develop/src/assets/lumio-component-rough-coal.svg"/><img src="https://cdn.rawgit.com/arcticicestudio/lumio/develop/src/assets/lumio-component-soft-earth.svg"/><br><img src="https://cdn.rawgit.com/arcticicestudio/lumio/develop/src/assets/lumio-component-hard-metal.svg"/><img src="https://cdn.rawgit.com/arcticicestudio/lumio/develop/src/assets/lumio-component-piquant-olive.svg"/><br><img src="https://cdn.rawgit.com/arcticicestudio/lumio/develop/src/assets/lumio-component-cold-snow.svg"/><img src="https://cdn.rawgit.com/arcticicestudio/lumio/develop/src/assets/lumio-component-clear-water.svg"/><br><img src="https://cdn.rawgit.com/arcticicestudio/lumio/develop/src/assets/lumio-component-hot-flame.svg"/><img src="https://cdn.rawgit.com/arcticicestudio/lumio/develop/src/assets/lumio-component-roasted-cocoa-bean.svg"/><br><img src="https://cdn.rawgit.com/arcticicestudio/lumio/develop/src/assets/lumio-component-tropical-wood.svg"/><img src="https://cdn.rawgit.com/arcticicestudio/lumio/develop/src/assets/lumio-component-fine-sand.svg"/><br><img src="https://cdn.rawgit.com/arcticicestudio/lumio/develop/src/assets/lumio-component-sweet-banana.svg"/><img src="https://cdn.rawgit.com/arcticicestudio/lumio/develop/src/assets/lumio-component-calm-sunset.svg"/><br><img src="https://cdn.rawgit.com/arcticicestudio/lumio/develop/src/assets/lumio-component-living-forest.svg"/><img src="https://cdn.rawgit.com/arcticicestudio/lumio/develop/src/assets/lumio-component-deep-sea.svg"/><br><img src="https://cdn.rawgit.com/arcticicestudio/lumio/develop/src/assets/lumio-component-fresh-wild-berries.svg"/></p>

### Documentations
All project documentations have been rewritten.  
The project license for the code has been changed to the [Apache 2.0](http://www.apache.org/licenses/LICENSE-2.0) license.
(@arcticicestudio, #2, 9edbcee1)

### Git
The `.gitignore` and `.gitattributes` files have been rewritten to remove the high amount of unused pattern and comments.
(@arcticicestudio, #2, 9edbcee1)

# 1.1.0 (2016-04-16)
## Improvements
### Color Palettes
  - Added a version number field and tag for the "JSON"- and "XML" color palette file formats
  - Removed unnecessary `element` and `colors` tags and fixed the whitespace indention of the XML file format color palette `lumio.xml`:

|               | Before   | After     | Reduction |
| ------------- | -------- | --------- | --------- |
| Lines of code | `1786`   | `872`     | `-914`    |
| File size     | `47.6kb` |  `20.1kb` | `27.5kb`  |

### Documentation
  - Updated all documentations to adapt to other Arctic Ice Studio project documentation formats
  - Changed the [Creative Commons](https://creativecommons.org) license to the [CC BY-SA-4.0](http://creativecommons.org/licenses/by-sa/4.0/) license type  
  [![CC BY-SA-4.0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](http://creativecommons.org/licenses/by-sa/4.0/)

## Bug Fixes
  - Fixed the corrupted GIMP `.xcf` project file
  - Moved the "GIMP/Inkscape Palette" (`lumio.gpl`) and "Alias/WaveFront Material" (`lumio.mtl`) files from the `content`- to the `native` folder

# 1.0.0 (2016-03-28)
## Features
  - Added native file formats:

| Type | Extension |
| ---- | --------- |
| <img src="http://www.adobe.com/favicon.ico" width=16 height=16/> Adobe Swatch Exchange     | `.ase` |
| <img src="https://www.gimp.org/images/wilber16.png" width=16 height=16/> GIMP Project      | `.xcf` |
| <img src="http://static.gpick.org/image/logo.png" width=16 height=16/> Gpick Color Palette | `.gpa` |

  - Added non-native application support file formats:

| Type | Extension |
| ---- | --------- |
| Alias/WaveFront Material | `.mtl` |
| <img src="https://www.gimp.org/images/wilber16.png" width=16 height=16/>/<img src="https://inkscape.org/favicon.ico" width=16 height=16/> GIMP/Inkscape Palette | `.gpl` |

  - Added non-native CSS preprocessor file formats:

| Type | Extension |
| ---- | --------- |
| <img src="http://lesscss.org/public/ico/favicon.ico" width=16 height=16/> LESSCSS | `.less` |
| <img src="http://sass-lang.com/favicon.ico" width=16 height=16/> Sass | `.scss` |

  - Added non-native data-structure representation file formats:

| Type | Extension |
| ---- | --------- |
| <img src="http://www.json.org/favicon.ico" width=16 height=16/> JSON | `.json` |
| <img src="https://www.w3.org/favicon.ico" width=16 height=16/> XML | `.xml` |

# 0.0.0 (2016-03-28)
**Project Initialization**
