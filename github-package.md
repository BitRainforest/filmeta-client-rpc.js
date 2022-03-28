# Github Package Use


## 前置

首先获取 [`Personal access token`](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token)

在根目录下新建 `.npmrc` 文件，内容如下：

```
@bitrainforest:registry=https://npm.pkg.github.com
//npm.pkg.github.com/:_authToken=<token>
```

将 `<token>` 替换为 `Personal access token`


## Publish

创建并填写完 `.npmrc` 文件后，运行 `npm publish` 即可。


## Install 
创建并填写完 `.npmrc` 文件后，运行 `npm install @bitrainforest/filmeta-client-rpc.js --save` 即可。

