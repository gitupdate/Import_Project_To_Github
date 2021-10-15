# Import_Project_To_Github

## 如何把新建的项目上传到github(注: 此教程是基于已有github账号,pc端安装了git,如没有安装git,请自行网上搜索安装)

#### 第一步：打开Github网站：https://github.com/   登录自己的账号。

#### 第二步：点击Your profile，进入仓库管理：

#### 点击 New 按钮,  新建一个仓库,然后输入仓库名称,描述等等

#### 仓库创建成功后, 我们利用https的方式来进行上传代码

#### 在你要上传的项目文件夹根目录鼠标右键,点击“Git Bash Here”，打开git命令行

#### 然后输入“git init”，使项目文件夹加入git管理

#### 接着输入 git add .   (注: 后面有个点 .)

#### 接着输入 输入  git commit -m "first commit"  (注: ""双引号里面,是提交信息,随你自己写)

#### 输入   git remote add origin  https://github.com/lxk0301/shopping-car.git （注: git remote add origin 是你自己的仓库https的地址），连接你的guthub仓库。

#### 输入“git push -u origin master”，这里可能会要求输入Github的账号密码(注: 如果是第一次,就需要输入github账号密码)，按要求输入就可以

#### 至此, 就结束了(注: [整个教程的图文参考链接](https://www.cnblogs.com/shenchanghui/p/7184101.html))

