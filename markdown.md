# 测试1
<!-- TOC -->

- [测试1](#测试1)
    - [标题](#标题)
- [h1](#h1)
    - [h2](#h2)
            - [h4](#h4)
    - [区块引用](#区块引用)
    - [列表](#列表)
    - [强调](#强调)
    - [链接](#链接)
    - [图片](#图片)
    - [代码区块](#代码区块)
    - [分隔线](#分隔线)
    - [反斜杠](#反斜杠)

<!-- /TOC -->

## 标题 

a first level
=============
the second level
----------------
# h1
## h2
#### h4
```
类Setext=最高阶标题-第二阶标题
类Atx这段文字行首加 # 号即可
```
##区块引用
>this is a blockquote

>>life is a flower
    
    每行的最前面加上 >

## 列表

* one
* two
+ one
+ two
- one
- two
1.one
2.two
3.three
* a list item with a blockquote
   >this is a blockquote
   >inside a list item

1986\. What a great season.
     
```
无序列表使用星号、加号或是减号作为列表标记
有序列表则使用数字接着一个英文句点

如果要在列表项目内放进引用，那 > 就需要缩进
避免随便出现列表的状况，你可以在句点前面加上反斜杠
```
##强调

*single*example

_single_example

**single8**example

__double__kill
```
星号（*）和底线（_）作为标记强调字词的符号
唯一的限制是，你用什么符号开启标签，就要用什么符号结束
```

## 链接

this is a [example link](http：//example.com)

this is an [example link](http://example.com/ "with a title")
i got one from[goole][1]than from[yahoo][2]

[1]:http://goole.com/"goole"

[2]:httpL://search.yahoo.com/ "yahoo search"
[gool][]

[gool]:http://gool.com/

<http://example.com/>
    
    只要是用方括号包起来自动把它转成链接

```
行内链接直接在后面用括号直接接上链接
参考形式的链接让你可以为链接定一个名称，之后你可以在文件的其他地方定义该链接的内容
隐式链接在后面加方括号即可,接着定义链接
```
## 图片

![alt text](/path/to/img.jpg "title")
![alt text][id]

[id]:ul/to/image "optional title attribute"
    「id」是图片参考的名称，图片参考的定义方式则和链接参考一样：

## 代码区块


i strongly recommend against using any `<blink>`tags

like `&dash;` instead
``there is a literal backtick (`)here``

A single backtick in a code span: `` ` ``
```
使用反引号 ` 来标记代码区段，区段内的 &、< 和 > 都会被自动的转换成 HTML 实体
如果要在代码区段内插入反引号，用多个反引号来开启和结束代码区段
```
    这是一个代码段
    这是一个代码区段
    （4个空格或1个制表符开始，以没有缩进结束）

## 分隔线

哈哈哈
***
呵呵呵
* * *
lalala
- - -
nanana
____
    一行中用三个以上的星号、减号、底线来建立一个分隔线，行内不能有其他东西

## 反斜杠

\*better\*
     
     反斜杠来插入一些在语法中有其它意义的符号


