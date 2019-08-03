# VanillaRoulette.js
-------------

`VanillaRoulette.js` - vanilla JavaScript library, which designed to rotate horizontal roulettes

## DEMO

You can see demo [here](https://kir-antipov.github.io/VanillaRoulette/sample/index.html) :)

## Usage

Using `VanillaRoulette.js` is really simple:

 1. **Link** `CSS` and `JS` to your page:

```html
<link href="libs/vanillaRoulette/vanillaRoulette.min.css" rel="stylesheet">
<script src="libs/vanillaRoulette/vanillaRoulette.min.js"></script>
```

2. **Create** a container for roulette and fill it with content blocks (you can use any tag filled with any content):

```html
<div id="roulette">
    <div>...</div>
    <div>...</div>
    <div>...</div>
    <div>...</div>
</div>
```

 3. **Initialize** the roulette (simply pass a unique selector to the `Roulette` constructor):
 
 ```js
 let roulette = new Roulette("#roulette");
 ```
 
  4. **Profit**

<br>
  
`VanillaRoulette` has a number of configurable options, so you're welcome to visit our [Wiki](https://github.com/Kir-Antipov/VanillaRoulette/wiki)!)