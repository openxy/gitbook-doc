# 安装指南
-------------------------  
## 一、nodebook安装
1.安装node.js  
2.使用node.js中的npm下载gitbook  
①打开命令提示符，输入:

```
$ npm install gitbook-cli -g
```  
②在安装gitbook的文件夹中创建一个新的文件夹，用于存放书的内容。例如：  
输入  
```$ mkdir webpack
```  
创建一个文件夹  
```
$ cd webpack  
```  
在命令提示符中进入这个文件夹  
③输入  
```
$ gitbook init
```  
初始化生成文件README.md和SUMMARY.md,分别用于放书的说明和放书的目录  
④在webpack目录中输入  
```$ gitbook serve```  
生成网址 
![示例](https://rails365.oss-cn-shenzhen.aliyuncs.com/uploads/photo/image/466/2017/5e2840a2da0a246fbeaf7b33b61fa364.png)   


##二、插件的安装
1.找到plugins插件列表  
2.输入你想添加的插件，示例添加chapter-fold插件(可以支持多层目录，点击导航栏的标题名就可以实现折叠扩展)  
①在```
book.json
```的pulgins参数中添加插件名：  
{  
　　　"plugins":["chapter-fold"]  
}  
②使用
```
npm install gitbook-plugin-chapter-fold
```
命令安装插件

