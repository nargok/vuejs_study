# Vue.jsメモ

## Vue.jsの基本設定

```javascript
var data = {
  message: "Please type!"
};

var app = new Vue({
  el: '#app',
  data: data
})
```
## ボタン

```html
<input onClick="doAction()" />
```

```javascript
function doAction() {
  data.message = "You Clicked!"; 
}
```

## インプットフィールド
```html
<input onInput="doAction(event)" />
```

```javascript
function doAction(event) {
  data.message = event.target.value;
}
```