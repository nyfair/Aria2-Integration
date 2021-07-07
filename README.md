# Aria2 Download Manager Integration
a Firefox Add-on to integrate with Aria2

https://addons.mozilla.org/firefox/addon/aria2-integration/

## Reference
https://github.com/aria2/aria2

https://github.com/mayswind/AriaNg

## Monkey Patch
* fix https/wss protocol
* configure download panel in addon popup menu
* integrate latest AriaNg

## AriaNg Modification
* index.html  
ng-app="ariaNg" **ng-csp**
* js/angular-packages-{version}.min.js  
https?|s?ftp|mailto|tel|file **|moz-extension**
