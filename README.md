# Proxy-commands
Proxy commands for various software

# NPM 

Set Proxy: 
`npm config set https-proxy http://proxy.company.com:8080`

Unset proxy: 
`npm config rm proxy
npm config rm https-proxy
unset HTTP_PROXY
unset HTTPS_PROXY
unset http_proxy
unset https_proxy
`

# GIT 
Set proxy: 
`git config --global http.proxy http://<username>:<password>@<proxy-server-url>:<port>`

Unset proxy: 
`git config --global --unset-all http.proxy # to remove it from the global config
git config --unset-all http.proxy  # to remove it from the local repo config file` 

# CONDA

Coming soon! 
