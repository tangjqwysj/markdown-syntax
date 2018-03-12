[TOC]
## 斜体和粗体
1. *斜体*
2. **粗体**
3. ***加粗斜体***
4. ~~删除线~~

## 分级标题
1. `# 一级标题`
2. `## 二级标题`
3. `### 三级标题`
4. `#### 四级标题`
5. `##### 五级标题`
6. `###### 六级标题`

## 超链接
1. 行内式
  欢迎来到[梵居闹市](http://blog.leanote.com/freewalk)
  欢迎来到[梵居闹市](http://blog.leanote.com/freewalk "梵居闹市")
2. 参考式
  我经常去的几个网站[Google][1]、[Leanote][2]以及[自己的博客][3]
  [Leanote 笔记][2]是一个不错的[网站][]。
    
    [1]:http://www.google.com "Google"
    [2]:http://www.leanote.com "Leanote"
    [3]:http://http://blog.leanote.com/freewalk "梵居闹市"
    [网站]:http://http://blog.leanote.com/freewalk

3. 自动链接 
  <http://example.com/> 
  <address@example.com>

## 锚点
## 目录{#index}

  跳转到[目录](#index) (似乎不会跳转)

## 列表
1. 使用 *，+，- 表示无序列表。
   - 无序列表项 一
   - 无序列表项 二
   - 无序列表项 三
2. 有序列表
    1. 有序列表项 一
    2. 有序列表项 二
    3. 有序列表项 三
3. 定义型列表 (似乎并不成功)

    Markdown
    :   轻量级文本标记语言，可以转换成html，pdf等格式（左侧有一个可见的冒号和四个不可见的空格）

    代码块 2
    :    这是代码块的定义（左侧有一个可见的冒号和四个不可见的空格）
    
            代码块（左侧有八个不可见的空格）

## 引用
>>> 请问 Markdwon 怎么用？ - 小白

>> 自己看教程！ - 愤青

> 教程在哪？ - 小白

## 插入图像
![美丽花儿](http://ww2.sinaimg.cn/large/56d258bdjw1eugeubg8ujj21kw16odn6.jpg "美丽花儿")

![美丽花儿][flower]

[flower]:http://ww2.sinaimg.cn/large/56d258bdjw1eugeubg8ujj21kw16odn6.jpg  "美丽花儿"

## 内容目录
在段落顶填写 [TOC] 以显示全文内容的目录结构。

## 注脚
使用 Markdown[^1]可以效率的书写文档, 直接转换成 HTML[^2], 你可以使用 Leanote[^Le] 编辑器进行书写。

[^1]:Markdown是一种纯文本标记语言

[^2]:HyperText Markup Language 超文本标记语言

[^Le]:开源笔记平台，支持Markdown和笔记直接发为博文

## 表格
1. 不管是哪种方式，第一行为表头，第二行分隔表头和主体部分，第三行开始每一行为一个表格行。
2. 列于列之间用管道符|隔开。原生方式的表格每一行的两边也要有管道符。
3. 第二行还可以为不同的列指定对齐方向。默认为左对齐，在-右边加上:就右对齐。

产品|价格
-|-:
Leanote 高级账号|60元/年
Leanote 超级账号|120元/年

## 分隔线
* * *
***
*****
- - -
---------------------------------------

## 代码
1. 行内式
 C语言里的函数 `scanf()` 怎么使用？
2. 多行代码
```
#include <stdio.h>
int main(void)
{
    printf("Hello world\n");
}
```

## HTML 原始码
<div class="footer">
   © 2004 Foo Corporation
</div>

<table>
    <tr>
        <th rowspan="2">值班人员</th>
        <th>星期一</th>
        <th>星期二</th>
        <th>星期三</th>
    </tr>
    <tr>
        <td>李强</td>
        <td>张明</td>
        <td>王平</td>
    </tr>
</table>
