##  Android 网络请求注意事项

- 使用Https协议需要证书
  - 如果是ca签发，一般情况下，可以直接访问；
  - 如果是自签的，访问前需要设置ssl相关配置；
- 使用http协议的url
  - 从Android P开始，默认不再允许直接访问http请求
  - 通过设置network security configuration支持；

## okhttp

