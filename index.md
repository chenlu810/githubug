<font size=7 color=gray face="黑体">操作手册</font>

# 一、登录
## 1.进入账户
[https://github.com/login](https://github.com/login) ，提交用户名密码。
## 2.进入团队
单击右下角习悦标志。

![avatar](images/图片1.png)
## 3.进入库
单击进入对应repository。

![avatar](images/图片2.png)
![avatar](images/图片3.png)

# 二、编辑
分本地和线上两种方式
## 1.本地编辑
### ①clone到本地

单击clone or download→复制库的地址→进入本地电脑文件夹（不要选择桌面），右键菜单左键单击clone到本地→关闭  

![avatar](images/图片4.png)
![avatar](images/图片5.png)
![avatar](images/图片6.png)
![avatar](images/图片7.png)
### ②修改文件
保持文件名不变，打开直接修改即可，修改之后的文件将出现红色感叹号，可单个文件提交到github库，也可批量提交。
**单个提交**：右键单击文件名→Git提交（C）“master”→撰写“日志信息”→提交并推送→关闭，提交成功后红色感叹号变为绿色对号

![avatar](images/图片8.png)
![avatar](images/图片9.png)
![avatar](images/图片10.png)
**批量提交**：在此文件夹根目录下空白处右键单击文件名→Git提交（C）“master”→撰写“日志信息”→提交并推送→关闭，提交成功后所有红色感叹号变为绿色对号

![avatar](images/图片11.png)
![avatar](images/图片12.png)
![avatar](images/图片13.png)

### ③添加文件
在根目录下放入新增文件或文件夹（不可为空）→根目录下空白处右键单击Git Bash Here→依次输入命令（见下方）→刷新库即可见更新后的内容
**命令**：复制粘贴（右键paste）单行后回车，新增原因按需修改。
>git add .
>git commit -m "新增原因"
>git push -u origin maste

![avatar](images/图片14.png)
![avatar](images/图片15.png)
![avatar](images/图片16.png)

## 2.线上编辑
### ①修改文件
单击需要修改的文件→单击编辑按钮→编辑→页面下方编写修改说明→commit changes

![avatar](images/图片17.png)
![avatar](images/图片18.png)
![avatar](images/图片19.png)
![avatar](images/图片20.png)

### ②添加文件
**添加单个文件**：
方法一：单击create new file→输入文件名称→编辑→页面下方编写修改说明→commit new file

![avatar](images/图片21.png)
![avatar](images/图片22.png)
![avatar](images/图片23.png)

方法二：单击upload files→单击choose your files→选定本地文件（可批量导入单个文件）→打开→上传完毕后呈白色状态→编写说明→commit changes

![avatar](images/图片24.png)
![avatar](images/图片25.png)

**添加文件夹**：

