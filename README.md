![image](https://github.com/user-attachments/assets/823eab9b-faf1-4fc9-b393-6bc595e54e23)# -
kotlin写的，附上转换好的exe安装包

原理就是利用selenium技术，模拟浏览器找网页元素进行点击，这里采用的是edge浏览器的模拟操作器，因此**项目在有edge浏览器的电脑上可以运行**。

最后也将打包好的jar包用jpackage进一步打包，这里给出的是exe安装包，将安装包下载之后安装得到文件夹，点击文件夹内的exe执行文件即可运行。

## 免责声明
可能存在许多漏洞：
- 使用了webdriver manager来自动匹配电脑上edge浏览器版本来自动下载驱动器，但webdriver manager似乎有什么安全漏洞，作者就懒得细究了
- 在找网页元素并点击的过程中，找的元素是根据类名来定位的，如果学校之后网站有所更改，代码也需相应更改，否则可能造成巨大损失
- 作者较懒，后期可能很少进行维护了，还望谅解
