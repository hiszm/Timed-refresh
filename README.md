# Timed-refresh（定时刷新)
https://greasyfork.org/zh-CN/scripts/419247

```js
// ==UserScript==
// @name         定时刷新
// @namespace    http://tampermonkey.net/
// @version      0.5   
// @description  定时刷新脚本
// @author       hiszm
// @match        *://*/*
// @grant        none
// @compatible   chrome
// @license      GPL-3.0
// ==/UserScript==
 
(function () {
'use strict';
 
setTimeout(function(){location.reload();}, 1000);
 
 
})();

```


