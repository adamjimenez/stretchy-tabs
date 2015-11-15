# ui.tabs.overflowResize
Chrome style tab-resizing for jQuery UI tabs

overflowResize provides methods for adding and removing tabs

##Initialize overflowResize
```
$( ".tabs" ).tabs("overflowResize");
```

##Methods:
* add
* remove

e.g.:
```
$( ".tabs" ).tabs("add", "new tab", "content goes here");
$( ".tabs" ).tabs("remove", index); //index is an integer for the tab position
```

##Events
* tabsbeforeremove,
* tabsremove,
* tabsadd

e.g:
```
$( ".tabs" ).on("tabsbeforeremove", func);
$( ".tabs" ).on("tabsremove", func);
$( ".tabs" ).on("tabsadd", func);
```

[Demo](http://jsfiddle.net/adamjimenez/1myo7uk3/1/)
