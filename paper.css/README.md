paper.css
=========
### Print
```javascript
var frm = document.getElementById("iframeResult").contentWindow;
frm.focus();// focus on contentWindow is needed on some ie versions
frm.print();
```
