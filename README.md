# 🎉 <a href="https://agezao.github.io/confetti-js" target="_blank">Confetti Generator</a> 🎉
Easily Generate random confetti with javascript and make your design look cooler

## Demo 🚀
<a href="https://agezao.github.io/confetti-js" target="_blank">Demo</a> // <a href="https://agezao.github.io/confetti-js/examples" target="_blank">Examples</a>

## Why?
Have you ever seen that cool looking confetti on landing pages and above-the-fold content? We give you the power to create the same effect for free and without the hassle of having to design or code it from scratch.

## Installing/Using
### 📲 Downloading
- Using `npm`

    ```bash
      npm install confetti-js --save
    ```

- Direct download -> [click here](https://github.com/agezao/confetti-js/archive/master.zip)

### ➕ Add scripts

```html
<script src="node_modules/confetti-js/dist/index.min.js"></script>
```

### 🤔 How to use it?
After installing the plugin(adding the ``<script />``), just call-it passing the options:
#### html
```html
<canvas id="my-canvas"></canvas>
```

#### javascript
```javascript
  <script>
    var confettiSettings = { target: 'my-canvas' };
      var confetti = new ConfettiGenerator(confettiSettings);
      confetti.render();
  </script>
```
done!

## Options

| Attribute | Description | Example value | Default value |
|---------------------------|-------------|---------------|---------|
| *`target`* | The Id tag of the canvas that will be used | 'my-canvas' | 'confetti-holder' |

## License
to-do
