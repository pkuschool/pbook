# 临时说明

启动人文项目合一测试。

目的
* 让更多人可以在一个平台一次性了解全部项目进度。
* 降低项目各自维护网站的学习与精力成本。

可能产生的问题
* 结构目录的特色。
* 使用同一repo，需要项目主管熟悉分支开发。
* gitbook以文字为主，是否满足项目呈现需讨论。

---
简明教程

* 先到[这里下载安装 Node.js](https://nodejs.org/en/)，在管理员权限下，打开命令行终端，输入：
```
npm install gitbook-cli -g
```
* 再点击[这里](https://git-scm.com/book/zh/v2/%E8%B5%B7%E6%AD%A5-%E5%AE%89%E8%A3%85-Git)，按说明安装git

* 之后，找个文件夹，启动git bash，输入
```
git clone https://github.com/pkuschool/cbook.git
```
* 之后，点击[这里](https://code.visualstudio.com/)安装vscode，使用其打开刚刚clone到的项目文件夹。
* 找到所主管项目项目：
   * 点击[学习markdown](https://www.runoob.com/markdown/md-tutorial.html)编辑项目内容。
   * 打开刚刚clone到的文件夹内SUMMARY,学习gitbook目录结构。
* 编写所主管项目内容:
   * 如添加新的md文件，记得在SUMMARY内加入路径。
   * 如添加图片，请使用“项目英文缩写+自定义编号”进行命名，放入images文件夹内。

* 本项目源文件在master，网站页面文件在gh-pages分支。所以，各项目内容编写完毕后，请在本repo新建项目子分支，push内容即可。