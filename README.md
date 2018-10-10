 # vue-nigeria-states-lgas
  
  
  [![NPM](https://nodei.co/npm/vue-nigeria-states-lgas.png?downloads=true)](https://nodei.co/npm/vue-nigeria-states-lgas/)
  
  [![npm version](https://badge.fury.io/js/vue-nigeria-states-lgas.svg)](https://badge.fury.io/js/vue-nigeria-states-lgas)
  
  A simple VueJs library that returns symbol of a country.
  
  ### Installation
  
  ``` Javascript
  
  npm install vue-currency-symbol
  
  ```
  
  ### Usage
  In the component where you want use Nigeria states and Lgas
  ```javascript

  import StatesLgas from 'vue-currency-symbol/dist/vue-currency-symbol.esm.js'

  ```
  Then register the component.
  
  ```javascript
  
  <script>
  
     ...
  
     import Vue from 'vue'
     
     import CurrencySymbol from 'vue-currency-symbol/dist/vue-currency-symbol.esm.js'
     
     Vue.use(CurrencySymbol)
     
     ...
  
  </script>
  
```
   
   Use `currencySymbol(countryName)` to get the corresponding country currency symbol
   
   #### Note
   Use as a value of `v-html` directive
   
   #### Example
  
   Adding `<span v-html="currencySymbol('japan')"></span>` to the element you want to use the symbol returns
   Japanese Yen symbol `// ¥`
   
 
    

 
