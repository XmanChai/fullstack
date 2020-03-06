# Ubuntu18 Tips
***

### 1 github.com fast access

modify the /etc/hosts file
```
13.250.177.223 github.com
140.82.113.3 github.com
185.199.109.154 github.githubassets.com
185.199.110.154 github.githubassets.com
185.199.108.154 github.githubassets.com
185.199.111.154 github.githubassets.com

151.101.88.133 avatars0.githubusercontent.com

185.199.108.153 assets-cdn.github.com
185.199.109.153 assets-cdn.github.com
185.199.110.153 assets-cdn.github.com
185.199.111.153 assets-cdn.github.com
199.232.5.194 github.global.ssl.fastly.net
192.30.253.119 gist.github.com

```

restart dns and refresh the cache
```
sudo systemctl restart systemd-resolved.service
```
