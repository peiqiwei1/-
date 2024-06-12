##关键字查询
xx(python) awesome: 查该标签下的xx(python)项目<br>


##GitHub 三要素 <br>
###Repository 仓库<br>
	仓库是github项目管理存储的基本单位<br>
	一个仓库中存储一个项目，一个用户可以拥有多个仓库，<br>
	一般仓库分为public，private<br>
###Commit 提交 <br>
	程序员在整个开发周期中，有大量的对代码的选代和修改，<br>
	都可以通过commit的方式进行记录，便于程序猿回溯代码，<br>
	即使这些代码被删除<br>
	提交便于使用者观察整个工程的开发流程以及设计流程<br>
###Branch分支<br>
	在仓库中可以包含多个分支，分支才是代码文件的第一存储单位<br>
	默认的仓库主分支为master/main * 不仅可以管理代码存储，也便于多人协作开发
<br>

###仓库内容<br>
Code，资源存储，代码资源，二进制，项目管理脚本，许可证等等。<br>
issues，使用时遇到bug 或进行提交 等待反馈。<br>
README,使用markdown语言编写，工程自述文件，开发进度，版本更新，使用介绍等<br>
LICENSE许可证：GPL2.0,3.0 Apache2.0,Mit，这些许可证，给使用者最大使用权限以及最少的限制。<br>

###Git软件，分布式版本控制系统<br>
仓库管理软件，使用git管理私人代码或企业代码<br>
 
##设备认证<br>
###1. 让网站的账户与设备绑定，后续完成代码的管理，上传下载<br>
```c
	git init   //创建本地仓库  *后续对仓库的操作，都要在仓库位置(master)
	git config -list  //查看git的配置文件

```
####修改或添加conofig配置项
```c
	git config --global user,name  //用户名
	git config --global user.email //注册邮箱
```
####生成本机设备密文
```c
	ssh -keygen -t rsa -C "注册邮箱"   //创建本地密文 
	去对应的目录下查找密文文件
```
rsa.pub复制密文，粘贴到settings->SSH key and GPG ->new ssh key -> 粘贴



####测试关联是否完成




Markdown 文本修饰语言 用特殊符号修饰正文效果<br>

##标题修饰符\#
#标题修饰符(一级标题)
##标题修饰符(二级标题)
###标题修饰符(三级标题)
####(四级标题)

##正文内容
  输入正文内容，但是如果需要换行，用\<br\> 标签

##修饰正文
  *一段测试文本*

  **一段测试文本**

  ***一段测试文本***

  ~~一段测试文本~~

##引用效果用\>表示
>你自己就是一座金矿，关键在于如何让挖掘和利用自己
>>苏格拉底
>>>三级引用
>>>>四级引用

##列表修饰符
###无序列表 \*
* 二次元游戏
  * 元神
    * 什么玩意
* 大逃杀类
  * PUBG
  * APEX

###有序列表
1. 物理学
  1.粒子物理
  2.原子物理
2. 计算机科学
  1.分布式架构
  2.云计算

### 混合列表
1. 测试一级
  * 测试二级
  2. 测试三级

### 表格
名称|技能|排行
--|:--:|--:
蝙蝠侠|有钱|32
海王|游泳|16
闪电侠|跑|18

###代码片段
```c

	#include<stdio.h>

	int main()
	{
		printf("test code\n");
		return 0;
	}

```

```cpp

	#include<iostream>
	using namespace std;

	int main()
	{
		cout<<"acd abc"<<endl;
		return 0;
	}
```

```python
	import <os>
```

```bash
	echo "测试"
	pwd
	ps aux
	ls -l
```





