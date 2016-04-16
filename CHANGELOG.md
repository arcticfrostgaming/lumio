Lumio
=====

## 1.1.0 (2016-04-16)
### Improvements
#### Color Palettes
  - Added a version number field and tag for the "JSON"- and "XML" color palette file formats
  - Removed unnecessary `element` and `colors` tags and fixed the whitespace indention of the XML file format color palette `lumio.xml`:

|               | Before   | After     | Reduction |
| ------------- | -------- | --------- | --------- |
| Lines of code | `1786`   | `872`     | `-914`    |
| File size     | `47.6kb` |  `20.1kb` | `27.5kb`  |

#### Documentation
  - Updated all documentations to adapt to other Arctic Ice Studio project documentation formats
  - Changed the [Creative Commons](https://creativecommons.org) license to the [CC BY-SA-4.0](http://creativecommons.org/licenses/by-sa/4.0/) license type  
  [![CC BY-SA-4.0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](http://creativecommons.org/licenses/by-sa/4.0/)

### Bug Fixes
  - Fixed the corrupted GIMP `.xcf` project file
  - Moved the "GIMP/Inkscape Palette" (`lumio.gpl`) and "Alias/WaveFront Material" (`lumio.mtl`) files from the `content`- to the `native` folder

## 1.0.0 (2016-03-28)
### Features
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

## 0.0.0 (2016-03-28) - Project Initialization
