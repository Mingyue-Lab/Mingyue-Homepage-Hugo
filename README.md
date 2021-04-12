# 明月网安首页 - 基于 [Hugo](https://gohugo.io/)
本项目为明月网安实验室首页项目，构建使用 [Hugo 0.82.0](https://github.com/gohugoio/hugo/releases/tag/v0.82.0) ，基于主题 [Somrat](https://github.com/somratpro/somrat)

项目中的 `hugo.exe` 为64位 Windows 版本，如需使用其他操作系统请访问 [Hugo Releases](https://github.com/gohugoio/hugo/releases) 下载。

**注意：**请勿上传任何敏感个人隐私信息。

### 如何本地预览
1. 进入 `Mingyue` 目录
2. 打开命令行并定位到此目录
3. 使用命令 `hugo server --themesDir ../`
4. 打开浏览器访问 `http://localhost:1313/`

### 如何构建可部署于服务器上的静态页面文件
1. 进入 `Mingyue` 目录
2. 打开命令行并定位到此目录
3. 使用命令 `hugo -F --gc --minify --themesDir ../`
4. 完成构建，构建后的文件在同目录的 `public` 文件夹下

### 其它链接
- [Hugo Github](https://github.com/gohugoio/hugo)
- [Hugo 主题列表](https://themes.gohugo.io/)
