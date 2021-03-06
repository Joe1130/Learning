# 标题

* 写法
    > **标题有两种写法**  
* 示例

1. 第一种

    > 一级标题
    > =
    >  二级标题
    > -
    > **这种写法只有两个标题**
2. 第二种
    > #  一级标题
    > ## 第二种 二级标题
    > ### 第二种 三级标题 
***

# 段落
* 写法
    > **段落空格需要两个以上空格加回车**
* 示例
    >哈喽  
    >我的   
    >哈喽
    >我的
***

# 字体
* 写法

    >斜体、粗体、粗斜体 ,   
    >*比_好用
* 示例
    > *斜体文本*  
    > _斜体文本_  
    > **粗体文本**  
    > __粗体文本__  
    > ***粗斜体文本***    
    > ___粗斜体文本___ 
***

# 分隔线
* 写法
    >**在一行中用三个以上的星号、减号、底线来建立一个分隔线**
* 示例   
  > ***
  > * * *  
  > ****
  > ---
  > - - -
  > ___
***

# 删除线
* 写法
  >**如果在段落上的文字加删除线，只需要在文字的两端加上两个~~即可**
* 示例
  >测试  
哈喽，~~清楚测试~~，世界   
***

# 下划线
* 写法
  > 下划线可以通过<u>标签来实现</u>
* 示例
  > 非测试内容   <u>测试内容</u> 哈罗  
  
# 脚注
* 写法
  >[^要注明的文本] ,脚注是对文本的说明
* 示例
  >经常看时间简史[^时间简史]  
  [^时间简史]: 霍金的作品
***

#列表
* 写法  
  1. 无序列表
     > 使用星号(*)、加号(+)或是减号(-)作为列表标记
  2. 有序列表
     >有序列表使用数字并加上 . 号来表示


* 示例
  1. 无序列表
     > * 第一项
     > * 第二项
     > * 第三项
 
     > + 第一项
     > + 第二项
     > + 第三项
 
     > - 第一项
     > - 第二项
     > - 第三项
  2. 有序列表
     > 1. 第一项
     > 2. 第二项
     > 3. 第三项
***

# 区块
* 写法
  >区块引用是在段落开头使用 > 符号 ，然后后面紧跟一个空格符号
* 示例
  > > 最外层
  > > > 第一层嵌套
  > > > > 第二层嵌套
***

# 代码
* 写法
  > 
  * 如果是段落上的一个函数或片段的代码可以用反引号把它包起来（`）
  * 代码区块使用 4 个空格或者一个制表符（Tab 键）
  * 你也可以用 ``` 包裹一段代码，并指定一种语言（也可以不指定）
* 示例
  > `Console.WriteLine("哈喽我的")`  
  > Console.WriteLine("哈喽我的")  

  > `Console.Wirte`
  > ```c#
  > console.writeLine() 
  > ```
***

# 链接
* 写法
  >链接使用方法如下：  
  > [链接名称](链接地址)  
  > 或者  
  > <链接地址>  

* 示例
  > [百度](www.baidu.com)
  ><www.baidu.com>

  > **高级链接**
  > 链接也可以用变量来代替，文档末尾附带变量地址：
  > 这个链接用 1 作为网址变量 [Google][1]  
  > 这个链接用 runoob 作为网址变量 [Runoob][runoob]  
  > 然后在文档的结尾为变量赋值（网址）  
  >  [1]: http://www.google.com/  
  >  [runoob]: http://www.runoob.com/  
***

# 图片
* 写法
  > ![alt 属性文本](图片地址)
  > ![alt 属性文本](图片地址 "可选标题")
* 示例
  > ![alt martdown](https://baike.baidu.com/pic/markdown/3245829/0/00e93901213fb80ef9ceac7132d12f2eb938947d?fr=lemma&ct=single#aid=0&pic=00e93901213fb80ef9ceac7132d12f2eb938947d)
***

# 表格
* 写法
  > |  表头   | 表头  |    
  > |  ----  | ----  |  
  > | 单元格  | 单元格 |  
  > | 单元格  | 单元格 |
  >> *对齐方式*
  >> * -: 设置内容和标题栏居右对齐。
  >> * :- 设置内容和标题栏居左对齐。
  >> * :-: 设置内容和标题栏居中对齐。
* 示例  
   > | 表头  | 表头 |
   > | :---: | :--- |
   > |   1   | 2    |
   > |   3   | 3    |
   > |   4   | 4    |
   > |   5   | 6    |