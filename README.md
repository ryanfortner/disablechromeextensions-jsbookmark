# disablechromeextensions-jsbookmark
disable a chrome extension with the click of a button

paste the following into a new chrome bookmark

```
javascript:prompt('Extension IDs here: (seperated by commas)').split(',').forEach(i=>{chrome.management.setEnabled(i.trim(),!1)}) 
```

you will need the extension ID of the extension you wish to disable.

from the folks on the TitaniumNetwork discord server.
