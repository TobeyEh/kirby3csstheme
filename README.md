# Kirby CSS theme
A CSS theme for Kirby 3

The CSS theme aims to be soft and friendly by using a light colour scheme, rounded border edges, light focus-outlines, mini-animations etc.
It also changes the design of some plugins to fit into the colour scheme.

## Examples

<img width="863" alt="Bildschirmfoto 2021-01-26 um 22 15 19" src="https://user-images.githubusercontent.com/66064484/105908705-d7c57d80-6026-11eb-928d-4fd0cbe15ffe.png">
<img width="463" alt="Bildschirmfoto 2021-01-26 um 22 15 10" src="https://user-images.githubusercontent.com/66064484/105908710-d8f6aa80-6026-11eb-89fb-1c5bdf8abd2f.png">
<img width="1621" alt="Bildschirmfoto 2021-01-26 um 22 14 53" src="https://user-images.githubusercontent.com/66064484/105908729-ddbb5e80-6026-11eb-95eb-fb831e0c2819.png">
<img width="463" alt="Bildschirmfoto 2021-01-26 um 22 15 10" src="https://user-images.githubusercontent.com/66064484/105908741-e01db880-6026-11eb-81d5-e80158774183.png">
<img width="1634" alt="Bildschirmfoto 2021-01-26 um 22 18 46" src="https://user-images.githubusercontent.com/66064484/105908763-e6139980-6026-11eb-9e2f-6de17306481a.png">


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


## Info

The file is autoprefixed using https://autoprefixer.github.io.

The CSS file aims to be styling all native elements however, since there are quite a lot, you can gladly report any missed elements or suggestions for improvement.
