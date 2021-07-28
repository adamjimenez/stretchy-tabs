# stretchy tabs
Chrome style tab-resizing for jQuery UI tabs

stretchy tabs provides methods for adding and removing tabs

##Initialize stretchy tabs
```javascript
$( ".tabs" ).tabs("stretchyTabs");
```

##Methods
* add
* remove

e.g:
```javascript
$( ".tabs" ).tabs("add", "new tab", "content goes here");
$( ".tabs" ).tabs("remove", index); //index is an integer for the tab position
```

##Events
* tabsbeforeremove,
* tabsremove,
* tabsadd

e.g:
```javascript
$( ".tabs" ).on("tabsbeforeremove", func);
$( ".tabs" ).on("tabsremove", func);
$( ".tabs" ).on("tabsadd", func);
```
##Demos
* [Standard](https://rawgit.com/adamjimenez/ui.tabs.overflowResize/master/demo/index.html)
* [Chrome Theme](https://rawgit.com/adamjimenez/ui.tabs.overflowResize/master/demo/chrome.html)
