# 目录


## 1.标题 
示例：
![标题](https://github.com/gegealice/aa-test/blob/master/markimage/1.png)

类Setext=最高阶标题-第二阶标题
类Atx这段文字行首加 # 号即可
## 2.区块引用
```
>this is a blockquote

>>life is a flower
```
示例：
![引用](https://github.com/gegealice/blob/master/markimage/2.1.png)

 每行的最前面加上
>引用的多层嵌套（引用之中有引用，根据层次的不同加不同数量的>）


## 3.列表

```
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
示例：
![列表](https://github.com/gegealice/aa-test/blob/master/markimage/3.1.png)

无序列表使用星号、加号或是减号作为列表标记
有序列表则使用数字接着一个英文句点

如果要在列表项目内放进引用，那 > 就需要缩进
避免随便出现列表的状况，你可以在句点前面加上反斜杠
包含引用的列表，>需要缩进
```
*  阅读的方法
   >打开书本
   >打开电灯
```
1.<代码写在这>
    
 如果要放代码区块的话，该区块就需要缩进两次，也就是 8 个空格或是 2 个制表符：
## 4.强调

    *single*example

    _single_ example

    **single8**example

    __double__ kill
示例：![强调](https://github.com/gegealice/aa-test/blob/master/markimage/4.1.png)

星号（*）和底线（_）作为标记强调字词的符号
唯一的限制是，你用什么符号开启标签，就要用什么符号结束

    ***加粗斜体*** ~~删除线~~
示例：![alt text](https://github.com/gegealice/aa-test/blob/master/markimage/4.2.png)

## 5.链接
```
this is a [example link](http：//example.com)

this is an [example link](http://example.com/ "with a title")
i got one from[goole][1]than from[yahoo][2]

[1]:http://goole.com/"goole"

[2]:httpL://search.yahoo.com/ "yahoo search"
[gool][]

[gool]:http://gool.com/
自动连接

<http://example.com/>
``` 
示例：![链接](https://github.com/gegealice/aa-test/blob/master/markimage/5.1.png)

 只要是用方括号包起来自动把它转成链接

行内链接直接在后面用括号直接接上链接
参考形式的链接让你可以为链接定一个名称，之后你可以在文件的其他地方定义该链接的内容
隐式链接在后面加方括号即可,接着定义链接

## 6.图片

     
    (1) ![alt text](/path/to/img.jpg "title")
     ep：
     ![alt text](https://github.com/gegealice/aa-test/markimage/cat.jpg "猫咪")
示例： ![猫咪](https://github.com/gegealice/aa-test/blob/master/markimage/cat.jpg "猫咪")  

    (2)：
    ![小狗][1]
    [1]:http://github.com/gegealice/aa-test/blob/master/markimage/dog.jpg  "小狗"
示例：
![小狗][1]

[1]:http://github.com/gegealice/aa-test/blob/master/markimage/dog.jpg  "小狗"
![图片Alt](图片地址 “图片Title”)

在文档要插入图片的地方写![图片Alt][标记] 

在文档的最后写上[标记]:图片地址 “Title”


## 7.代码区块

```
i strongly recommend against using any `<blink>`tags

like `&dash;` instead
there is a literal backtick (`)here``

A single backtick in a code span: `` ` ``
```

使用反引号 ` 来标记代码区段，区段内的 &、< 和 > 都会被自动的转换成 HTML 实体
如果要在代码区段内插入反引号，用多个反引号来开启和结束代码区段
 这是一个代码段这是一个代码区段（4个空格或1个制表符开始，以没有缩进结束）

## 8.分隔线
```
哈哈哈
***
呵呵呵
* * *
lalala
- - -
nanana
```
示例：![alt text](https://github.com/gegealice/aa-test/tree/master/markimage/8.1.png)
____
一行中用三个以上的星号、减号、底线来建立一个分隔线，行内不能有其他东西

## 9.反斜杠
     \*better\*
反斜杠来插入一些在语法中有其它意义的符号
## 10. 锚点
markdown extra 只支持在标题后插入锚点，其他地方无效
在你准备跳转到的制定标题后插入锚点{#标记}，然后在文档的其他地方写上连接到锚点的链接
    
    ## 0.目录{#index} 
    跳转到[目录](#index)
## 10.注脚
在需要添加注脚的文字后加上脚注名字[^注脚名字],称为加注。 然后在文本的任意位置(一般在最后)添加脚注，脚注前必须有对应的脚注名字

注脚与注脚之间必须空一行，不然会失效
     [^1]:Markdown是一种纯文本标记语言
## 11.LaTeX 公式
$ 表示行内公式

      质能守恒方程可以用一个很简洁的方程式 $E=mc^2$ 来表达。
$$ 表示整行公式：
      
      $$\sum_{i=1}^n a_i=0$$

      $$f(x_1,x_x,\ldots,x_n) = x_1^2 + x_2^2 + \cdots + x_n^2 $$

      $$\sum^{j-1}_{k=0}{\widehat{\gamma}_{kj} z_k}$$
    
## 12.流程图
```
flow
st=>start: Start:>https://www.zybuluo.com
io=>inputoutput: verification
op=>operation: Your Operation
cond=>condition: Yes or No?
sub=>subroutine: Your Subroutine
e=>end

st->io->op->cond
cond(yes)->e
cond(no)->sub->io
```
示例：![alt text](https://github.com/gegealice/aa-test/tree/master/markimage/12.1.png)
## 13.表格
```
     学号|姓名|分数
     -|-|-
     小明|男|75
     小红|女|79
     小陆|男|92
```
示例：![alt text](https://github.com/gegealice/aa-test/blob/master/markimage/13.1.png)
https://github.com/gegealice/aa-test/blob/master/markimage/12.1.png

原生方式写表格：
```
|学号|姓名|分数|
|-|-|-|
|小明|男|75|
|小红|女|79|
|小陆|男|92|
```
示例：![alt text](https://github.com/gegealice/aa-test/tree/master/markimage/13.2.png)
为表格第二列指定方向

产品|价格
-|-：
leanote 高级账号|60元一年
leanote 超级账号|120元一年
示例：![alt text](https://github.com/gegealice/aa-test/tree/master/markimage/13.3.png)



