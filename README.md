# markdown使用笔记



## 不同数量的#加空格是不同级别的标题

> 引用: >加空格



1. 有序列表(数字.加空格)



- 无序列表(-加空格)



- [ ] 勾选列表(- [ ] (一共3个空格))

- [x] 勾选列表(- [x] (一共2个空格))



```c
int main()
    //```语言
```



```java
public void test()
```


$$
数学公式:$$ 内,\代号{} ,如 2\sqrt{1}
$$


表格: 新开一行的    |表头|表头|...|    在下一行写对齐方式|:---|---:|:---:|(typora不适用)

| 表   | 头   |
| ---- | :--- |
|      |      |

| :--- | ---: | :---: |
| ---- | ---- | ----- |
|      |      |       |



这是[^脚注],写法是内容后面[]里面加^内容,需要补充脚注内容(复制加:)

[^脚注]: 就像这样,可以跳转

比如[^教主]

[^教主]: 



三个-是横线

---

以上是块级元素

以下是行内元素

---



链接:  [](网址"注释")       [百度](baidu.com "eg")

引用链接: 把( "")替换为[],[]里面填id  然后[id]: 网址"注释"

[引用][id]

[id]: baidu.com "引用链接"



### 标题

标题跳转[标题][### 标题]     也是两个[]   标题名字要一样



url:

http://www.baidu.com



图片:上面的网址前加个!和[],  后面加个()填充图片地址

![图片](www.baidu.com)



**斜体    *这样*

****加粗    **这样**

``行内代码      

`这样`

<u>下划线</u>

$$行内数学公式

$\theta$  用$包围

下标  H~2~O 用~包围

高亮==包围 

==这样==



分享->嵌入代码->直接复制









