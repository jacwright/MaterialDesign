# Material Design

This repo contains all the planning for current and work-in-progress Material Design Icons.

[Getting Started for Bootstrap](http://materialdesignicons.com/bootstrap) - [Getting Started for Other Platforms](http://materialdesignicons.com/getting-started)

[![npm](https://img.shields.io/npm/v/@mdi/font.svg)](https://www.npmjs.com/package/@mdi/svg) [![npm](https://img.shields.io/bower/v/mdi.svg)](https://www.npmjs.com/package/@mdi/svg) [![GitHub issues](https://img.shields.io/github/issues/Templarian/MaterialDesign.svg)](https://github.com/Templarian/MaterialDesign/issues) [![npm](https://img.shields.io/npm/dm/@mdi/font.svg)](https://github.com/Templarian/MaterialDesign-Webfont) + (renamed `mdi` [![npm](https://img.shields.io/npm/dm/mdi.svg)](https://github.com/Templarian/MaterialDesign-Webfont))

<sub>Download stats above only for NPM</sub>

## Icons

View at [Material Design Icons](http://materialdesignicons.com/). This repo also contains converted icons from [Google's official icon set](https://github.com/google/material-design-icons).

|                 | NPM                   | Bower                   | Dist Repo |
|-----------------|-----------------------|-------------------------|-----------|
| Webfont / SCSS  | `npm install @mdi/font`     |`bower install mdi`      | [MaterialDesign-Webfont](https://github.com/Templarian/MaterialDesign-Webfont) |
| JavaScript / TypeScript  | `npm install @mdi/js`     | n/a      | [MaterialDesign-JS](https://github.com/Templarian/MaterialDesign-JS) |
| ReactJS  | `npm install @mdi/react`     | n/a      | [MaterialDesign-React](https://github.com/Templarian/MaterialDesign-React) |
| SVG / Meta.json | `npm install @mdi/svg` | `bower install mdi-svg` | [MaterialDesign-SVG](https://github.com/Templarian/MaterialDesign-SVG)     |

[![Icons](http://i.imgur.com/zKuXEkR.png)](https://materialdesignicons.com/)

**Note:** _SVG icons are not compressed in GitHub. Please use the icons from [Material Design Icons - Design](http://materialdesignicons.com/design) or [Templarian/MaterialDesign-SVG](https://github.com/templarian/materialdesign-svg) if you need inline SVG._

**Warning (Cordova only):** _You will need to manually edit the css file to remove the version query string. [Read More](https://github.com/Templarian/MaterialDesign/issues/760)._

## Contribute

Please do not make pull requests against this repositiory. All icons are managed through the Material Design Icons site by the various contributors. If you want to become a contributor [read more](http://materialdesignicons.com/contribute).

### Icon Suggestions

Submit icon suggestions through the issue tab. Please include examples.

### Expression Design (.design) and SVG

[Expression Design](http://www.microsoft.com/en-us/download/details.aspx?id=36180) is a freeware software for designing vector assets. All icons are also provided in SVG which can be opened by most vector editors.

For those designing new icons please use the templates provided as a starting point.

### Third Party (Plugins / Extensions / etc)

Please follow official releases and use the `@mdi/svg` [NPM](https://www.npmjs.com/package/@mdi/svg) dependency for any third party integration. This ensures a stable release for your plugins or third party libraries/applications.

[Templarian/MaterialDesign-SVG](https://github.com/templarian/materialdesign-svg)

```
npm install @mdi/svg
bower install mdi-svg
```

## License

Templates - [WTFPL](http://www.wtfpl.net/)

Community Icons - [SIL Open Font License 1.1](http://scripts.sil.org/cms/scripts/page.php?item_id=OFL_web)

Google Material Design Icons - [Apache License 2.0](https://github.com/google/material-design-icons/blob/master/LICENSE)

## Code of Conduct

[View and submit violations](https://materialdesignicons.com/code-of-conduct).
