# ETStore
ETLab资料库源码

## 用途
用于文件包含漏洞实验

# ！！！请注意，该工程含有漏洞，千万不要应用于生产环境

### 环境要求
php+mysql+apache(或者其他web中间件)

### 登录配置
默认用户名与密码参见sql文件

### 功能(文件存储)
1.上传文件，仅允许上传zip，doc，docx
2.文件列表处可以直接下载文件


#### v0.2版本
0.2版本目前已启动开发，但暂未发布，仍处于内测阶段


#### v0.3版本
0.3版本增加权限分离功能，普通用户功能与v0.2类似，管理员后台增加登录日志审核
0.3版本修改默认管理员密码，也可自己md5加密后替换数据库内容
0.3版本新增体验用户(普通权限)store_user1，密码
