
# Vtex Lazyload
A [Lazysizes](https://github.com/aFarkas/lazysizes) based plugin Lazyload for Vtex Components.

## Instalation
`$ npm install vtex-lazyload`

```html
<!-- CSS -->
<link rel="stylesheet" href="/arquivos/vtex-lazyload.min.css" media="all"/>
<!-- Javascript -->
<script type="text/javascript" src="/arquivos/vtex-lazyload.min.js"></script>
```

## Usage
```html
<!-- Vitrine -->
<div class="your-class js--lazyload has--lazyload" data-noscript="">
  <noscript>$product.GetImageTag(30)</noscript>
</div>
```
```html
<!-- Placeholder -->
<div class="your-class js--lazyload has--lazyload" data-noscript="">
  <noscript><vtex:contentPlaceHolder id="Main-Banner" /></noscript>
</div>
```

**Setting custom styles**
You can use the following classes to custom style:
```css
.is--lazyloaded { /* Uses when element is visible */ }
.has--lazyloading { /* Uses when element is loading */ }
.has--lazyerror { /* Uses when element has an error */ }
```

## License
Vtex Lazyload and Lazysizes is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).

## Credits
[Lazyzises](https://github.com/aFarkas/lazysizes) and all contributors!
