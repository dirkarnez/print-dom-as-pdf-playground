paper.css
=========
### Notes
- Must use iframe to isolate style
- Can use local font

### Print
```javascript
var frm = document.getElementById("iframeResult").contentWindow;
frm.focus();// focus on contentWindow is needed on some ie versions
frm.print();
```

### Tutorials
- [Responsive data tables with CSS Grid | by Daniel Salvado | Evodeck Software | Medium](https://medium.com/evodeck/responsive-data-tables-with-css-grid-3c58ecf04723)
