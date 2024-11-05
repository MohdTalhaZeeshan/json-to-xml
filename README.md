# json-to-xml
%dw 2.0
output application/xml
var details = {"name" : "raju"} 
---
c:
{
a:details,
b:details
}

output : 
<?xml version='1.0' encoding='UTF-8'?>
<c>
  <a>
    <name>raju</name>
  </a>
  <b>
    <name>raju</name>
  </b>
</c>
