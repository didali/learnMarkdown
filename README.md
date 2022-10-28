# study git and markdown

# 关于Typora和MarkDown

### 功能快捷键

```java
关于Typora中的一些常用快捷键
    撤销：Ctrl/Command + Z
    重做：Ctrl/Command + Y
    加粗：Ctrl/Command + B
    斜体：Ctrl/Command + I
    标题：Ctrl/Command + {1,2,3,4,5,6}
	段落：Ctrl/Command + 0
    链接：Ctrl/Command + K
    查找：Ctrl/Command + F
    替换：Ctrl/Command + H
    源代码模式：Ctrl/Command + ?
    引用：Ctrl/Command + Shift + Q
    任务列表：Ctrl/Command + Shift + X
    无序列表：Ctrl/Command + Shift + ]
    有序列表：Ctrl/Command + Shift + [
    插入链接：Ctrl/Command + Shift + L
    插入图片：Ctrl/Command + Shift + I
    显示\隐藏侧边栏：Ctrl/Command + Shift + L
```

### 页眉

`---`在第一行是页眉，在别的地方是分割线

---

先按`---`再回车，就形成了上述的分割线的效果

### 目录

`[toc]+回车，就会自动创建一个目录，效果如下 `

[toc]

### 标题

```java
在文件前面添加一个到六个 # 可以分别代表一级标题到六级标题；
	# 1			快捷键Ctrl + 1
    ## 2		快捷键Ctrl + 2
    ### 3		快捷键Ctrl + 3
    #### 4		快捷键Ctrl + 4
    ##### 5		快捷键Ctrl + 5
    ###### 6	快捷键Ctrl + 6
    (注意#和标题描述之间存在一个空格)
```

### 列表

无序列表可以在文字前面添加`*`、`+`、`-`号然后空格，三种符号任意选择一种即可，即可创建无序列表，效果如下

- 
- - - - 

有序列表，直接在数据后面加上英文的句号，然后空格就可以了

1. 
2. 1. 

## 引用

> 使用一个>来创建引用
>
> > 我们同时可以再使用>创建嵌套引用

### 任务列表

任务列表可以来帮助我们了解自己未完成和完成了的项目，如下：

- [ ] 我们可以创建任务列表
- [ ] 这需要我们使用 `- []` 
- [ ] 在创建任务列表之后我们可以通过前面的勾选框改变任务状态

### 代码块

Typora仅支持GitHub Flavored Markdown 中的栅栏式代码块，不支持 markdown 中的原始代码块

我们可以通过````之后输入一个可选的语言标识符，然后回车即可创建我们所需要的语言的代码块`

```java
//这是我通过 ```Java 创建的一个Java的代码块
    
public class {
    public static void main(String[] args) {
        System.out.print("hello world!");
    }
}
```



## 1.1 字体

*斜体字*

_斜体字_

**粗体字**

__粗体字__

***粗斜体***

___粗斜体___

## 1.2 分割线

***

---

为了兼容性



---



我们得在分割线前后均添加空白行



## 1.3 删除线和下划线

使用两个波浪线创建

~~这些字带有删除线~~

<u>下划线</u>

[^要注明的文本]





## 1.5 列表语法

有序列表，在每个列表项前面添加一个数字并且紧跟一个英文句点。数字不必按照数学顺序排列，但是列表应当从数字1开始

1. 1
   1. 1.1
   2. 1.2
2. 2
3. 3
4. 4

无序列表，在每个列表项前面添加破折号(-)、星号(*)、加号(+)。都可以创建

- A
- * B
  * + C

##  1.6 代码语法

`int i = 100`

``dwd wad awd aw `dawda w`awd aw aw d``



