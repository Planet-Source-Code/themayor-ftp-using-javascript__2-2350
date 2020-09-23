<div align="center">

## FTP \(Using Javascript\!\!\!\)


</div>

### Description

Well, I stumbled upon this when using geocites... I always kept timeing out! lol so anyways i remembered a way to to it through the url ie ftp://whoever:password@ftpsite

So i've made an ftp program.. i've tested it... and i've never timed out! lol not yet anyways.. So i decided to submit it even though it's not very complicated becuase psc.com didn't have one..

Happy Programming :)

~kc~
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[theMayor](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/themayor.md)
**Level**          |Beginner
**User Rating**    |4.1 (29 globes from 7 users)
**Compatibility**  |
**Category**       |[Internet/ Browsers/ HTML](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/internet-browsers-html__2-68.md)
**World**          |[Java](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/java.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/themayor-ftp-using-javascript__2-2350/archive/master.zip)





### Source Code

```
<html>
<head>
<script language="javascript">
function ftp()
{
 function returnvals()
 {
 return document.info.name.value;
 return document.info.pass.value;
 return document.info.ftpsite.value;
 }
 var nam=document.info.name.value
 var pas=document.info.pass.value
 var ftpsi=document.info.ftpsite.value
 if (nam=="")
 {
 alert('Please Enter a Name!')
 }
 else if (pas=="")
 {
 alert('Please Enter a Password!')
 }
 else if (ftpsi=="")
 {
 alert('Please Enter a FtpSite!')
 }
else
{
 top.location="ftp://"+nam+":"+pas+"@"+ftpsi+""
}
}
</script>
<title>Ftp Anyone?</title>
</head>
<body bgcolor="black">
<font face="tahoma" size="6" color="yellow"><center>
<u>Ftp Anyone?</u><br><hr color="lime"><br></center>
<table>
<form name="info">
<table>
<tr>
<td><font color="yellow">
<u>Name:</u>
</td>
<td>
<input type="text" size="12" name="name">
</td>
</tr>
<tr>
<td><font color="yellow">
<u>Password:</u>
</td>
<td>
<input type="password" size="12" name="pass">
</td>
</tr>
<tr>
<td><font color="yellow">
<u>FtpSite</u>
</td>
<td>
<input type="text" size="12" name="ftpsite">
</td>
</tr>
<tr>
<td><br><font color="yellow">
[<input type="button" style="font-family:tahoma" style="border style:none" style="background:black" style="color:lime" value="Submit" onClick="ftp()">]
[<input type="reset" style="font-family:tahoma" style="border style:none" style="background:black" style="color:lime" value="Clear">]
</td>
</td>
</tr>
</table>
</form>
</body>
</html>
```

