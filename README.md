# Kirby CSS theme
A CSS theme for Kirby 3

The CSS theme aims to be soft and friendly by using a light colour scheme, rounded border edges, light focus-outlines, mini-animations etc.
It also changes the design of some plugins to fit into the colour scheme.

## Examples



## Installation

1. Copy the file into the Kirby `assets/` folder.

2. Register the CSS file in the Kirby `config.php` file located at `/site/config/config.php` using

```
return [
  'panel' => [
    'css' => 'assets/css/custom-panel.css'
  ]
];
```
https://getkirby.com/docs/reference/system/options/panel#custom-panel-css

The file is autoprefixed using https://autoprefixer.github.io.

The CSS file aims to be styling all native elements however, since there are quite a lot, you can gladly report any missed elements or suggestions for improvement.
