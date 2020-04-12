# English

### [How To - Toggle Dark Mode | W3schools](https://www.w3schools.com/howto/howto_js_toggle_dark_mode.asp)
Body Class: Change the class for the `<body>` to override the CSS for each theme
```html
<body class="dark-mode">
```
```css
body {
  background-color: white;
}
body.dark-mode {
  background-color: black;
}
```


-----
### [Dark Mode in CSS | Css-tricks](https://css-tricks.com/dark-modes-with-css/)
```css
@media (prefers-color-scheme: dark) {
```


-----
### [How to create a dark\light mode switch in CSS and Javascript | Codyhouse](https://codyhouse.co/blog/post/dark-light-switch-css-javascript)
CSS Variables + Body data attribute
```css
:root {
  --color-bg: #ffffff;
}
[data-theme="dark"] {
  --color-bg: #000000;
}
body {
  background-color: var(--color-bg);
}
```
```html
<body data-theme="dark">
```


-----
### [Dark and Light theme switcher using CSS variables and pure JavaScript | Medium](https://medium.com/@haxzie/dark-and-light-theme-switcher-using-css-variables-and-pure-javascript-zocada-dd0059d72fa2)
https://codepen.io/haxzie/pen/xxKNEGM  
CSS Variables + `<Html>` Class
```html
<html class="theme-dark">
```
```javascript
localStorage.setItem('theme', 'theme-dark');
document.documentElement.className = 'theme-dark';
```


-----
### [Create A Dark/Light Mode Switch with CSS Variables | dev.to](https://dev.to/ananyaneogi/create-a-dark-light-mode-switch-with-css-variables-34l8)
https://codepen.io/ananyaneogi/pen/zXZyMP  
https://ananyaneogi.com/  
CSS Variables + `<Html>` data attribute
```html
<html data-theme="dark">
```
```css
:root {
    --primary-color: #302AE6;
    --secondary-color: #536390;
    --bg-color: #fff;
}
[data-theme="dark"] {
    --primary-color: #9A97F3;
    --secondary-color: #818cab;
    --bg-color: #161625;
}
body {
    background-color: var(--bg-color);
}
```
```javascript
localStorage.setItem('theme', 'theme-dark');
document.documentElement.setAttribute('data-theme', 'dark');
```

-----
**Dark/Light Mode Switcher**  
https://codepen.io/HarlemSquirrel/pen/NdMebZ
