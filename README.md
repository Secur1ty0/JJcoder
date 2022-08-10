## 说明

jjencode/jjdecode将JS代码转换成只有符号的字符串，为了解决网页在线不能加解密大文件而手写的js脚本。



## 用法

需要nodejs环境支持，nodejs官网：http://nodejs.cn/。

```bash
# 加密
node ./jjcoder.js  -e '$' app.js
# 解密
node ./jjcoder.js  -d app-encode-result.js 
```

