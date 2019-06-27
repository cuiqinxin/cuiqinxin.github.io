# MarkDown语言与Typora工具介绍



## MarkDown介绍

> **Markdown **是一种轻量级标记语言，创始人为 John Gruber。它允许人们「使用易读易写的纯文本格式编写文档，然后转换成有效的 XHTML（或者 HTML）文档」。



### 使用场景

- 各类代码托管平台

  主流的代码托管平台，如 GitHub、GitLab、BitBucket、Coding、Gitee 等等，都支持 Markdown 语法；

  很多开源项目的 README、开发文档、帮助文档、Wiki 等都用 Markdown 写作。

  在线Api文档、技术文档工具ShowDoc

- 技术社区和写作平台

  StackOverflow、CSDN、掘金、简书、GitBook、有道云笔记

- 论坛

  V2EX、光谷社区

### Markdown 的优点如下：

- 纯文本，所以兼容性极强，可以用所有文本编辑器打开。
- 让你专注于文字而不是排版。
- 格式转换方便，Markdown 的文本你可以轻松转换为 html、电子书等。
- Markdown 的标记语法有极好的可读性。



## MarkDown语法指南



### 标题

MarkDown中标题分为六级，设置标题非常简单只需在文字前添加对应数量的 `#` 号即可，如图所示一级标题为	 `# 一级标题 `  ，二级标题为 `## 二级标题`，之后同理。

**Markdown：**

```
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题
```

**预览效果：**

> # 一级标题
>
> ## 二级标题
>
> ### 三级标题
>
> #### 四级标题
>
> ##### 五级标题
>
> ###### 六级标题





### 字符效果

对段落或者部分文本的强调效果。

**Markdown：**

```
~~删除线~~
*斜体字*
**粗体**
***粗斜体*** 
<u>下划线</u>
上标：X<sub>2</sub>，下标：O<sup>2</sup>
```

**预览效果：**

> ~~删除线~~
> *斜体字*
> **粗体**
> ***粗斜体*** 
>
> <u>下划线</u>
>
> 上标：X<sub>2</sub>，下标：O<sup>2</sup>





### 引用

**Markdown：**

```
> 引用块段落一。
>
> 引用块段落二。
>> 内嵌引用块段落一。
>
> ### 引用块内的标题
```

**预览效果：**

> 引用块段落一。
>
> 引用块段落二。
> > 内嵌引用块段落一。
>
> ### 引用块内的标题





### 代码与代码块

**Markdown:**

```
执行命令：`npm install`来安装依赖

​```javascript
function test() {
	console.log("Hello world!");
}
​```
```

**预览效果：**

执行命令：`npm install`来安装依赖

```javascript
function test() {
	console.log("Hello world!");
}
```





### 列表

包括有有序列表，无序列表，任务列表

**Markdown：**

```
有序列表
1. 有序列表一
2. 有序列表二
3. 有序列表三

无序列表：
- 无序列表一
- 无序列表二
- 无序列表三

* 无序列表一
* 无序列表二
* 无序列表三

无序列表嵌套
+ 列表一
+ 列表二
    + 列表二-1
    + 列表二-2
    + 列表二-3
+ 列表三
    * 列表一
    * 列表二
    * 列表三
```

**预览效果：**

有序列表
1. 有序列表一

2. 有序列表二

3. 有序列表三

   

无序列表：
- 无序列表一

- 无序列表二

- 无序列表三

  

* 无序列表一

* 无序列表二

* 无序列表三

  

无序列表嵌套
+ 列表一
+ 列表二
    + 列表二-1
    + 列表二-2
    + 列表二-3
+ 列表三
    * 列表一
    * 列表二
    * 列表三





### 任务列表

**Markdown：**

```
- [x] 洗碗
- [ ] 清洗油烟机
- [ ] 拖地
```

**预览效果：**

- [x] 任务一
- [ ] 任务二
- [ ] 任务三



### 链接

**Markdown：**

```
[普通链接](https://www.baidu.com/)
[普通链接带标题](https://www.baidu.com/ "百度")
直接链接：<https://www.mdeditor.com>

引用式 [百度][1] 链接。
引用式 [百度][2] 链接，带标题。
[1]: https://www.baidu.com
[2]: https://github.com/mzlogin "百度主页"

邮箱地址链接：[mailto:test.test@gmail.com](mailto:test.test@gmail.com)
邮箱地址自动链接: test.test@gmail.com  <www@vip.qq.com>
```

**预览效果：**

[普通链接](https://www.mdeditor.com/)
[普通链接带标题](https://www.mdeditor.com/ "百度题")
直接链接：<https://www.mdeditor.com>  



引用式 [百度][1] 链接。
引用式 [百度][2] 链接，带标题。

[1]: https://www.baidu.com
[2]: https://www.baidu.com "百度主页"



邮箱地址链接：[mailto:test.test@gmail.com](mailto:test.test@gmail.com)
邮箱地址自动链接 :  test.test@gmail.com  <www@vip.qq.com>



### 图片

在普通链接（可带标题，可采用引用式）的写法前加一个 `!`，就是引用图片的方法。

**Markdown：**

```
![Alt text](https://mazhuang.org/favicon.ico "favicon")
```

**预览效果：**

![Alt text](https://mazhuang.org/favicon.ico"favicon")





### 分割线

使用一个单独行里的三个或以上 `*`、`-` 来生产一条水平分割线，它们之间可以有空格。

**Markdown：**

```
***

-----

- - -
```

**预览效果：**

***

-----

- - -

---





### 表格

注意表头与表身中间一行，`:`号的位置控制本列对齐方式，默认左对齐

**Markdown：**

```
| 编号  | 姓名（左） | 性别（中） | 年龄（右） |
| ----- | :-------- | ：---------: | ------: |
| 0     | 张三       | 28         | 男         |
| 1     | 李四       | 29         | 男         |
```

**预览效果：**

| 编号 | 姓名（左） | 年龄（右） | 性别（中） |
| ---- | :------ | ------: | :-----: |
| 0    | 张三       |         28 |     男     |
| 1    | 李四       |         28 |       男     |





### 特殊符号

**Markdown：**

```
&copy; &  &uml; &trade; &iexcl; &pound;
&amp; &lt; &gt; &yen; &euro; &reg; &plusmn; &para; &sect; &brvbar; &macr; &laquo; &middot;
X&sup2; Y&sup3; &frac34; &frac14;  &times;  &divide;   &raquo;
18&ordm;C  &quot;  &apos;
```

**预览效果：**

&copy; &  &uml; &trade; &iexcl; &pound;
&amp; &lt; &gt; &yen; &euro; &reg; &plusmn; &para; &sect; &brvbar; &macr; &laquo; &middot;

X&sup2; Y&sup3; &frac34; &frac14;  &times;  &divide;   &raquo;

18&ordm;C  &quot;  &apos;

> 注：详情参考[html实体](https://baike.baidu.com/item/HTML%E5%AE%9E%E4%BD%93)





### emoji

以 GitHub Pages 为例。

**Markdown：**

```
:camel: :blush: :smile:
```

**预览效果：**

:camel: :blush: :smile:





### 嵌入 HTML

Markdown 标记语言的目的不是替代 HTML，也不是发明一种更便捷的插入 HTML 标签的方式。它对应的只是 HTML 标签的一个很小的子集。

对于那些没有办法用 Markdown 语法来对应的 HTML 标签，直接使用 HTML 来写就好了。







> 参考文档：
>
> ​	<https://mazhuang.org/2018/09/06/markdown-intro/>
>
> ​	<https://www.mdeditor.com/>