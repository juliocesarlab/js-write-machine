
# js-write-machine

Javascript class to simulate a write machine effect



![functionalities preview](https://github.com/juliocesarlab/assets/blob/main/CPT2202271407-1344x651.gif)


## Get started
you can copy and paste code or install it from npm (recommended)

### Using npm
````bash
  npm i js-write-machine 
````

### Using yarn
````bash
  yarn add js-write-machine
````
### Vanilla JS
````html
  <!--after paste the content, turn your main script a module (so you can use import/export statements) -->
  <script **type="module"** src="your-script-path.js"> </script>

  <!-- Inside your main script -->
  <script>
    import WriteMachine from "./writeMachine.js";

    const phrasesArray = ["I love to Code", "Hello World", "Welcome !"];
    const htmlElement = document.querySelector('.myElement');
    const typeSpeed = 100;

    new WriteMachine(phrasesArray, htmlElement, typeSpeed).alternatePhrases()
  </script>
````

## Examples

```javascript
 import WriteMachine from "writeMachine"

const phrases = ["I love to Code", "Hello World", "Welcome !"];
const htmlElement = document.querySelector('.myElement');
const typeSpeed = 200;

new TypeMachine(phrasesArray, htmlElement, typeSpeed).alternatePhrases()
```

