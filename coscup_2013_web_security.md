COSCUP 2013 Handson Web Security
===================================

  * [Apt attack](http://en.wikipedia.org/wiki/Advanced_persistent_threat)，
    從旁邊的人入侵內部電腦。
  * [tor](http://zh.wikipedia.org/zh-tw/Tor)
  * 追蹤攻擊，可以從來源，也可以看誰連到來源，所以跨國跳兩層就很難追
  * [rainbow table](http://www.freerainbowtables.com)，
    要手動把zh改成en才能[下載](https://www.freerainbowtables.com/en/tables2/) XD
  * 電腦被控制後，包含週邊產品，像是web cam、麥克風，就都可以開關啦
  * 水會從木桶最低的地方流，所以大家都要學資安啦
  * web error msg 可以透漏什麼？
    * table schema
	* real path -> server os, distribution, application
  * 網站被hack紀錄，[zone-h](http://www.zone-h.org/)，計分板...


### 攻擊類型

  * 跳板
  * 換網頁
  * 偷密碼


Google Hacking
------------------

  * 無技術門檻，記得看 cache ，不要看本頁 XD
  * 找 google 爬了哪些頁面，看有沒有 
    * err msg, 
	* passwd, 
	* sensitive dir, ex 後台
  * operator:
    * site, can target any level of url, ex `site:edu.tw`
	* intitle
	* inurl, specific url, ex `site:xxx.xxx.tw inurl:admin`
	* filetype/ext
  * combination:
    * use '-' to remove www, or popular( may be more secure ) page, ex:
	  `site:xxx.gov.tw -site:www.xxx.gov.tw`
	  小網站可能是測試的、暫時的站台
	* specific msg
	  `'welcome to phpmyadmin' 'create new database' ext:php site:edu`, 
	  `mysql_connect ext:inc`

Resource
------------

  * [Mantra](http://www.getmantra.com/): firefox + security related plugin
    - [ext list](http://www.getmantra.com/tools.html), hackbar!
  * [burp](http://portswigger.net/burp/), proxy & attack，可以直接改 proxy 封包
  * [war game exercise](http://edu.dev-core.net/)
  * [dvwa](http://www.dvwa.co.uk/) Damn Vulnerable Web Application, 自學
  * [web goat](https://www.owasp.org/index.php/Category:OWASP_WebGoat_Project), 自學


