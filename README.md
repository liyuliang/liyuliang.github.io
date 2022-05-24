Blog 's Hexo Code
---

### Development environment
```
Ubuntu 16.04.1 LTS
npm -v
6.9.0
node -v
v10.16.3

hexo -v
hexo: 3.9.0
hexo-cli: 4.3.0
os: linux 5.4.0-67-generic Ubuntu 20.04.2 LTS (Focal Fossa)
http_parser: 2.8.0
node: 10.16.3
v8: 6.8.275.32-node.54
uv: 1.28.0
zlib: 1.2.11
brotli: 1.0.7
ares: 1.15.0
modules: 64
nghttp2: 1.39.2
napi: 4
openssl: 1.1.1c
icu: 64.2
unicode: 12.1
cldr: 35.1
tz: 2019a
```

#### Install hexo by npm

```
sudo npm install -g hexo-cli
```

#### Check the project
```
git clone https://gitee.com/liyuliang/blog.git
```

#### Install dependence in this project
```
cd hexo
npm install
```

#### Start local web server
```
hexo s
```

#### Fix bug
```
Node Sass does not yet support your current environment
```

```
cnpm rebuild node-sass
```

```
cnpm install node-sass@latest
cnpm install hexo-renderer-scss@latest
cnpm install hexo-renderer-sass@latest
```
