https://github.com/go-gost/gost/releases
~~~
wget  "https://github.com/go-gost/gost/releases/download/v3.0.0-rc7/gost_3.0.0-rc7_$(go env GOOS)_$(go env GOARCH).tar.gz"
tar zxf gost_3.0.0-rc7_$(go env GOOS)_$(go env GOARCH).tar.gz -C /usr/local/bin/
gost -L=socks5://user:passwd@:1080
nohup gost -L=socks5://user:passwd@:1080 >/dev/null 2>&1
~~~
