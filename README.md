aso.github.io
=============

Some un-clever API aren't well handled window.name.

purge_window_name.html will clean a window.name. 

Greaseemonkey userscript can erase window.name by 
```JavaScript
location.href = 'javascript:(function(){window.name="";})();'
```
