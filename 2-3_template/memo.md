# Template構文

## 属性に値をバインドする bind

書き方
```
v-bind: 属性名 = "設定する値"
```

例
```html
<p v-bind:style="style">{{ message }}</p>
```

```javascript
var data = {
  message: Hello, Vue.js,
  style: 'font-size:20pt; color:red;'
}
```