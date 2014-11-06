#### Privilege Escalation Level 02 - Privileged service

Use level2's account to read level3's encrypted password.  
Then I use John the Ripper to crack it. Read this: <http://securityoverride.org/downloads/john-the-ripper-examples.txt>  
Wordlist is very helpful.
  
If you can't login and have to input password again and again, try
```javascript
var userip='8.8.8.8';
```
in your JavaScript console. 
