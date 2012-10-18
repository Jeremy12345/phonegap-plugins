# show/hide softkeyboard plugin for Phonegap Android #

## Usage ##
Assuming this html:

&lt;button id="keyboard"&gt;Toggle Keyboard&lt;/button&gt;


This javascript should do something useful:

var softkeyboard = window.cordova.plugins.SoftKeyBoard;

$('#keyboard').toggle(softkeyboard.show, softkeyboard.hide);
