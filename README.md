# 一.标题
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题

没有七级标题  
双空格加回车换行哦！
不加就换不了！

# 二.字体
*斜体*
**加粗**
***斜体和加粗***
~~加删除线~~

>引用
>>嵌套应用
>>>>>>>>甚至可以嵌套n个，然而并没有什么卵用

************
这是分割线，用三个或以上的***
************


# 三.图片
![图片的名字](https://raw.githubusercontent.com/wRuanMing/HelloWorld/master/demo.jpg)

# 四.超链接
[超链接文字](http//www.baidu.com, "超链接的title，但鼠标移动到超链接文字上时显示的内容")
[超链接到三](# 三.图片)

# 五.列表
- 无序号列表
   - 多加三个空格就成了嵌套列表
      - 再来下一级的列表
1. 有序号列表
2. 有序号列表2号
3. 有序号列表3号
   - 嵌套一下
      1. 嵌套一下有序号列表，序号自动变a了哈哈！
# 六.表格
表头|表头|表头
:-: | :-: | :-: 
内容|内容|内容
内容|内容|内容
# 七.代码
`print("将单行代码用反引号包起来")`
```
print('如果是多行代码的情况')
print('就用三个反引号包起来')
```
# 八.流程图(GitHub里貌似不支持 )
```flow
st=>start: 开始
op=>operation: My Operation
cond=>condition: Yes or No?
e=>end
st->op->cond
cond(yes)->e
cond(no)->op
&```
