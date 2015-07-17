针对中文,演示Markdown的语法

大标题
===================================
  大标题一般显示工程名，类似html的h1<br />
  你只要在标题下面跟上=====即可（超过3个=即可，长度不限）<br />
  或者你可以在标题前面加一个 # 来实现（# 大标题）

中标题
-----------------------------------
  中标题一般显示重点项，类似html的h2<br />
  你只要在标题下面输入-----即可（超过3个-即可，长度不限）<br />
  或者你可以在标题前面加两个 # 来实现（## 中标题）

### 小标题
  小标题类似html的h3<br />
  你只要在标题前面加三个 # 即可（### 小标题）<br />
  **注意，下面所有语法的提示我都先用小标题提醒了！**

#### 四级标题
##### 五级标题
###### 六级标题
  四、五、六级标题类似html的h4、h5、h6<br />
  由前面类推，你只要在标题前面加四个、五个、六个 # 来实现<br />

### 水平标尺
----------
  你只要在一个空行画上-----即可（超过3个-即可，长度不限）<br />
  但注意，前一行不能有纯文字，否者会当作中标题处理！

### 文本框  
    这是一个有多行的文本框
    常用来在这里写入代码
    只要每行文字前面输入一个Tab（或四个空格）
    再输入文字，即可实现效果

  比如我们可以在多行文本框里输入一段代码,来一个C++版本的HelloWorld吧

	#include <iostream>
	using namespace std;
	
	int main(){
		cout<<"HelloWorld!"<<endl;
		return 0;
	}

### 链接
1.[点击这里你可以链接到Google](http://www.google.com)<br />
2.[点击这里我你可以链接到我的GitHub](https://github.com/tangxiadi)<br />
链接插入的格式是：\[链接的显示文字\]\(链接URL\)

### 图片
![github](https://avatars0.githubusercontent.com/u/9555093?v=3&s=256 "我的GitHub头像")<br />
图片插入的格式是：\!\[图像替代文本\]\(图片URL "图片说明文字"\)

### 图片链接
  比如我想点击GitHub的图片，然后再进入GitHub首页<br />
[![image](https://github.com/images/modules/dashboard/bootcamp/octocat_setup.png "GitHub")](http://www.github.com/)<br />
图片链接插入的格式是：\!\[\[图像替代文本\]\(图片URL "图片说明文字"\)\]\(链接URL\)

### 引用
> 段落前面用竖线来框定要引用的文字<br />
> 只要再文字前面加上> 即可<br />
> 但> 只能放在行首才有效<br />

### 多重引用
> 段落前面用竖线来框定要引用的文字<br />
> > 只要再文字前面加上> 即可<br />
> > > 但> 只能放在行首才有效<br />

### 无序列表

* 在行首加点
* 行首输入*
* 再空格，输入内容即可

### 有序列表
1. 在行首加数字标号
2. 行首输入数字和一个点（2.）
3. 再空格，输入内容即可

### 字体
* *斜体*只需要在要加斜体的文字前后各加上一个\*号即可（\*要加斜体的文字\*）
* **粗体**只需要在要加粗体的文字前后各加上两个\*号即可（\*\*要加粗体的文字\*\*）

### 特殊字符
有一些特殊字符如<,#等,只要在特殊字符前面加上转义字符\即可<br />
你想换行的话其实可以直接用html标签\<br /\>
