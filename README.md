# react-jianshu-login

## 服务器地址 106.75.76.122:80

```js
yarn
npm run start

```

## nginx 代理配置

``` nginx
location /api {
  proxy_pass http://conduit.productionready.io;  # uri为'/svr1'
}
```
