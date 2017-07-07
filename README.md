# sublime-less-error
sublime gulp打包less，报错如下错误：
unable to interpret argument clean-css-if it is a plugin(less-plugin-clean-css), 
make sure that it is installed under or at the same level as less。

- npm install -g less(lessc -v检查是否成功，以管理员身份运行命令)
- npm install less-plugin-clean-css

### 安装Sublime 插件 

安装方法：ctrl+shift+p>install Package>输入less2css按Enter


### 安装lessc

有了npm，安装lessc也是一行就可以了：

> npm install less -gd

安装完成之后，在Terminal中输入命令lessc试试，如果出现如下提示则表示安装成功：

> lessc: no input files

PS: 这时可以在Sublime Text 2中打开或者新建一个less文件，按下Ctrl+S保存，此时应该会在less文件的相同目录下生成同名的css文件。

参考链接：
http://www.cnblogs.com/alantao/p/6490863.html
https://fdream.net/blog/article/783.aspx
