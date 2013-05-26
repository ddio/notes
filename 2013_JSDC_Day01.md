Markdown
=========
  - [list] (http://stackoverflow.com/questions/8800385/recommendations-of-static-site-generator-which-accepts-markdown-documents)
  - [docpad?] (http://docpad.org/)

JS History & Public Cloud
==================

JavaScript -> try to build another x-OS platform, by Netscape
Mocha - LiveScript -> JavaScript


Flow Control
==================

Async Method in JS
---------------------------
  - Continuous-Passing Style
  - deep function in function => flow control
  - function depends on multiple calls => flow control

Flow Control
------------------
how about debuging?

async.js: use a handle to track status

promise pattern:  promise.then( succ, fail )
  - Ref: [CommonJS Promise/A] (http://ithelp.ithome.com.tw/question/10118894?tag=ithome.nq)
  - Ref: [Q framework] (https://github.com/kriskowal/q)  [Stack overflow] (http://stackoverflow.com/questions/14978630/promise-with-q-framework-and-the-callback-pattern-in-node-js)

function() {
	return [ f1().promise, f2().promise ];
}.then( function() {
	echo "async f1 & f2 is done~~";
});


ECMA-262 Edition 6: generator, cannot be called in async, need promise's help



網站效能調校
==========
  - 原來 debugger 有 profiling，每個瀏覽器都有
  - jsperf
  - [youtube record] (http://www.youtube.com/user/doggy8088/videos)


Ruby 
=======
  - [slide] (http://xdite.github.io/jsdc-2013-slide/#Cover)
  - [slide display] (https://github.com/shower/shower)

iCook 經驗談
==============
  - [介紹新功能] (http://usablica.github.io/intro.js/)
  - [給業務和行銷改網頁內容] (http://www.google.com/tagmanager/)

前端工程師的資安挑戰
==============
  - [OWASP] (https://www.owasp.org/index.php/Main_Page)
  - 要幫忙清 passwd cache in input 
  - 要用白名單，不要用黑名單，只接受能控制的
  - [CSRF] (https://en.wikipedia.org/wiki/Cross-site_request_forgery)
  - [Clickjacking] (http://en.wikipedia.org/wiki/Clickjacking)
  - [ClickJacking Test] (http://www.cirt.net/clickjack-test)
  - one time token


做更快一點 工程師討生活工具介紹
======================
  - vim
    - [search] (https://github.com/kien/ctrlp.vim)
  - sublime text
    - column selection
    - multi selection
    - goto anything, include file, function ( path keyword like browser url parsing )
  - LiveReload, auto reload when file changed
  - 容易畫圖，[skitch] (http://evernote.com/intl/zh-tw/skitch/)
  - 配色，[kuler] (https://kuler.adobe.com/)


Usability & Performance
=================
  - 抓到斷線後，不只提醒，也要阻止user繼續點
  - pjax
  - [Slide] (http://mei.homin.com.tw/Keynote_plain_and_vanity_yahoo.html)
  - 不同tab之間可用web storage/cookie來作data sync
  - pageVisibility, 讓程式知道現在tab 不在focus
  - [web sql database] (http://bigone2000.pixnet.net/blog/post/83672383-web-sql-database%E5%AF%A6%E4%BD%9C)
  - 根據解析度給不同圖片 [sencha] (http://www.sencha.com/products/io/)
