# 环境部署

###### [安装和设置Chrome](#安装和设置chrome)

###### [搭建Python环境](#搭建python环境)

###### [安装MONGODB](#安装mongodb)

---

### 安装和设置Chrome

* 用deployment/installers/里的安装文件来安装Chrome
* 安装deployment/extensions/文件夹里的插件
* 配置插件Html Content Blocker，打开image和media开关

![](/assets/content_blocker.png)

* 配置插件Random User-Agent, 按照下面截图选择配置

![](/assets/ua.png)

---

### 搭建Python环境

* 用deployment/installers/里的安装文件来安装Miniconda
* 启动Anaconda Prompt （用管理员身份）

* 输入以下命令安装虚拟环境， 把path改为depolyment\tmall\_spider的系统路径

`conda create -n tmall_spider --clone path`

---

### 安装MongoDB

* 用deployment/installers/里的安装文件来安装MongoDB



