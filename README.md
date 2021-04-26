# README #

Shareable [Browserslist](https://github.com/browserslist/browserslist) config for [ftrack](https://ftrack.com).

### Installation ###

Installation

```
yarn add --dev @ftrack/browserslist-config
```

### Usage ###

Configuration in package.json

```
{
  "browserslist": [
    "extends @ftrack/browserslist-config"
  ]
}
```

To support Qt5-based applications, include both:

```
{
  "browserslist": [
    "extends @ftrack/browserslist-config"
    "extends @ftrack/browserslist-config/qt5"
  ]
}
```

### Publishing changes ###

```
yarn publish --access public
```
