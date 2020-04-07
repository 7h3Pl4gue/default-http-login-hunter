
# Default HTTP Login Hunter

The **default-http-login-hunter.sh** is a tool capable of checking more then 380 different web interfaces for default credentials. It is based on the [NNdefaccts](https://github.com/nnposter/nndefaccts) alternate fingerprint dataset maintained by nnposter.


```
# Usage:
default-http-login-hunter.sh [-vvv] <URL|urls.txt|update>

# Example with a single URL:
default-http-login-hunter.sh 10.10.0.1
default-http-login-hunter.sh 10.10.0.1:80
default-http-login-hunter.sh https://10.10.0.1:443/
default-http-login-hunter.sh http://10.10.0.1:9999/

# Example with a list of URLs:
default-http-login-hunter.sh urls.txt

# To get the latest fingerprints:
default-http-login-hunter.sh update
```

For more information, visit https://www.infosecmatter.com/hunter-of-default-logins-web-http/

