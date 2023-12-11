Nginx Proxy with Javascript and custom cookies

Support bypassing cloudflare WAF

Using : 

make sure the njs module is installed you can read the documentation for install https://docs.nginx.com/nginx/admin-guide/dynamic-modules/nginscript/

copy nginx.conf to /etc/nginx

copy proxy.js to /etc/nginx/njs

open nginx.conf and edit line 11 with your domain

open proxy.js and edit line 12 and 15 with the target url and your domain

get your cookies txt with curl and edit proxy.js line 3 with your cookies

restart nginx