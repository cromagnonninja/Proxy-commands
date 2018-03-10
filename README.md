# Proxy-commands
Proxy commands for various software
Proxies working: 172.31.1.3/4/5/6

# NPM 

Set Proxy: 
`npm config set https-proxy http://172.31.1.5:8080`\

Unset proxy:   
`npm config rm proxy`\  
`npm config rm https-proxy`\  
`unset HTTP_PROXY`\  
`unset HTTPS_PROXY`\  
`unset http_proxy`\  
`unset https_proxy`\  


# GIT 
Set proxy: 
`git config --global http.proxy http://<username>:<password>@172.31.1.4:8080`\

Unset proxy: 
 - To remove it from the global config: 
`git config --global --unset-all http.proxy`
 - To remove it from the local repo config file:
`git config --unset-all http.proxy` 

# BOWER
In your `.bowerrc` file, make the following changes: 

.bowerrc:
`{`\
  `"directory": "bower_components",`\ 
  `"proxy": "http://172.31.1.4:8080",`\
  `"https-proxy":"http://172.31.1.4:8080",`\
  `"no-proxy":"myserver.mydomain.com"`\
`}`
