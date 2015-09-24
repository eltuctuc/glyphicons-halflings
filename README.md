
# glyphicons-halflings

This is Sass (Syntactically Awesome StyleSheets) based stylesheet generator for GLYPHICONS Halflings.

## Building

Just install all deps and call `gulp`

```shell
npm install
gulp
```

## Inject into Bootstrap 4

As Bootstrap 4 will drop GLYPHICONS support you can use this project to simply inject icons into their CSS.

Modify `_variables.scss` and change it to:

```Sass
$glyphicons-halflings-class-prefix: glyphicon !default;
$glyphicons-halflings-font-base-size: 12px !default;
$glyphicons-halflings-include-bonus: false !default;
```
