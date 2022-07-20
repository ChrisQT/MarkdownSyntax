# Markdown语法

### 一、标题

```markdown
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题
```



### 二、引用

```markdown
> 这是第一级引用。
>
> > 这是第二级引用。
>
> 现在回到第一级引用。
```

- 效果图：

> 这是第一级引用。
>
> > 这是第二级引用。
>
> 现在回到第一级引用。



### 三、列表

#### 3.1无序列表

```markdown
- Red
- Green
- Blue
```

- 效果图：

- Red
- Green
- Blue

#### 3.2 有序列表

```markdown 
1. Red
2. Green
3. Blue
```

- 效果图：

1. Red
2. Green
3. Blue

#### 3.3待办列表

```markdown
- [ ] 不勾选
- [x] 勾选
```

- 效果图

- [ ] 不勾选

- [x] 勾选



### 四、代码

#### 4.1 程序段

~~~markdown
```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```
~~~

- 效果图：

```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```

#### 4.2 斜体

```markdown
*Coding，让开发更简单*
_Coding，让开发更简单_
```

- 效果图：

*Coding，让开发更简单*
_Coding，让开发更简单_ 

#### 4.3 加粗

```markdown
**Coding，让开发更简单**
__Coding，让开发更简单__
```

- 效果图:

**Coding，让开发更简单**
__Coding，让开发更简单__ 



### 五、自动链接

```markdown
[Google](http://google.com)
```

- 效果图：

[Google](http://google.com)



### 六、表格

```markdown
First Header | Second Header | Third Header
------------ | ------------- | ------------
Content Cell | Content Cell  | Content Cell
Content Cell | Content Cell  | Content Cell
```

- 效果图：

| First Header | Second Header | Third Header |
| ------------ | ------------- | ------------ |
| Content Cell | Content Cell  | Content Cell |
| Content Cell | Content Cell  | Content Cell |



### 七、分割线

```markdown
这是分隔线上部分内容
---
这是分隔线下部分内容
```

- 效果图：

这是分隔线上部分内容

---

这是分隔线下部分内容



### 八、图片

```markdown
![Alt text](/path/to/img.jpg)
或
![Alt text](/path/to/img.jpg "Optional title")
```

效果图

![1552032531626](https://img-blog.csdnimg.cn/20190310151823587.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L011cnBoeV9z,size_16,color_FFFFFF,t_70)

