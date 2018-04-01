# Installation
Just highlight the code and then drag it to your bookmark bar

# For Discord
- Rainbow background for every message! (just like the april fools @someone rainbow!) 
```js
javascript:(function(a){a=document.createElement('style');a.innerHTML='.message-text:last-child{background:-webkit-gradient(linear,right top,left top,from(rgba(255,0,0,.2)),color-stop(rgba(255,255,0,.2)),color-stop(rgba(0,255,0,.2)),to(rgba(0,0,255,.2)));background:linear-gradient(270deg,rgba(255,0,0,.2),rgba(255,255,0,.2),rgba(0,255,0,.2),rgba(0,0,255,.2));border-radius:4px}';document.head.appendChild(a);})();
```
- Invisible messages!
```js
javascript:(function(a){a=document.createElement('style');a.innerHTML='.message-text:last-child{visibility:hidden;}';document.head.appendChild(a);})();
```
