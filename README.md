# DiscordHack
Привет а вот и скрипт


```js
1.


function login(token) {
setInterval(() => {
document.body.appendChild(document.createElement `iframe`).contentWindow.localStorage.token = `"${token}"`
}, 50);
setTimeout(() => {
location.reload();
}, 2500);
}


2.


login("token")


```
