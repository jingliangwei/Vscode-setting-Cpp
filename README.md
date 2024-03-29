# Vscode-setting-Cpp
# 注意配置完成记得重启vscode（重启可以解决80%的问题）
## 在vscode搭建C++运行环境
由于vscode不是一款IDE（集成开发环境），其本身不能直接运行C++程序，故需要配置外置编译器。我在网上查阅了许多资料，大多数是使用MinGW和visual studio 2022自带的MSVC这两种。  
但是网上的配置教程里的 c_cpp_properties.json、launch.json和tasks.json 这三个配置文件并不能在我的本地完成配置。在经过连续几天的摸索，我终于成功配置好了这两种编译器。为了帮助其他跟我一样的新手小白能够早点用上vscode来编写C++代码，同时备份一下自己的配置文件，以便后面参考，故创建这个仓库。  
具体详细的配置过程请参考以下2篇文章，这些文章也帮助了我完成大部分的配置工作，在此一并致谢。  
> 只需从一下2中编译器中选择一种即可，若想了解2种编译器的区别请自行google
1. 使用MinGW编译器
* [从零开始的vscode安装及环境配置教程(C/C++)(Windows系统)](https://blog.csdn.net/qq_45807140/article/details/112862592)
2. 使用MSVC编译器
* [VSCode配置C++环境（MSVC）](https://blog.csdn.net/qq_38981614/article/details/99629597)

如果读者按照文章中的说明已经完成了配置，则不用理会仓库里的配置文件，如果跟我一样遇到了问题，可以尝试一下使用仓库里的配置
> 要注意区分是使用哪种编译器，2种编译器对应的配置文件不同。    

## 在vscode配置使用easyx图形库
> 注意配置使用easyx图形库使用的是MinGW编译器

在大量地浏览并尝试网上各种教程后，最终找到一个能够成功的教程，如下：[VSCode配置MSVC+VSCode使用easyx库,2021.5.13日配置~~](https://www.cnblogs.com/zaunekko/p/14774675.html)

**再次对本仓库所引用所有文章作者表示感谢，如有侵权请联系我删除。**
