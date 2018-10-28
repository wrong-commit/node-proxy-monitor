# node-proxy-monitor
 A NodeJS / Squid 4.0 based malicious, javascript injecting proxy with a Node backend for data retreival

# Installation  
- Install Squid 4.2 with OpenSSL support. This is not compiled into the binaries available in the Debian 
9 repos, so will have to be done manually. These are the flags needed when running `./configure`:    
>--enable-ssl --enable-ssl-crtd --with-openssl  
- ~Setup a .env file, by running `$ cp env_template .env` and populating the correct values~ TODO: setup server.js to respect these settings
