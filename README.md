#CodeIgniter-Language
A CI spark for making auto-detecting the proper language to serve easy.

##Default auto detection flow
1. Check the lang code in the subdomain. It's the master rule.
2. Check the lang code in the first segment in URI.
3. If no lang code is in subdomain or URI check the browser language if available and activated.
4. As the last rule, set the lang code to the default one defined in the CI global config file.


##Credit
Rewrite of the kitlang language spark by Eric@devtime.com


