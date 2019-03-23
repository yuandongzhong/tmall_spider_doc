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

* 下载并安装Miniconda
  * [https://docs.conda.io/en/latest/miniconda.html](https://docs.conda.io/en/latest/miniconda.html)
* 启动Anaconda Prompt （用管理员身份）

* 移动到/deployment/路径， 输入以下命令安装虚拟环境 

`conda env create -f env.yml`

---

### 安装MongoDB

* 用deployment/installers/里的安装文件来安装MongoDB



