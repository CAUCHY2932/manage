
## python cookbook



1 数据结构和算法

1.1 将序列分解为单独的变量

```python
p = (4, 5)
x, y = p
data = [1, 2, 3, 4, 5]
a, b, c, d, e = data
```

> 记住的是，元素一定要匹配

函数编程

魔术方法

## 基础编程

## 系统编程



## 正则



## 网络



## 面向对象

### class 后面加不加括号
对于python3和python2而言，是有区别的，涉及到新式类和旧式类，一般的，我们统一不加括号。
但是有以下情况，我们需要加：
1.需要显示声明我们是新式类，这时候，我们需要在括号里加上object
2.继承。当我们需要继承一个基类时，我们必须带上括号

### 类方法
对于一个类，我们定义方法时，可以在上面加一个装饰器，当我们加上classmethod时，就定义了一个类方法，这让我们使用类时，无需进行初始化，即可直接调用类方法。与此同时，我们需要在方法内部加一个cls，类似于self
### 静态方法

静态方法，使得我们无需进行生命

### 属性property

### 普通的self

### 类属性和初始化





## 标准库



### os模块

- os.getcwd()获取当前文件目录
- os.walk()在目录树种游走输出在目录中的文件名，向上或者向下
- os.chmod()更改权限
- os.chown()更改文件所有者
- os.chdir()更改当前工作目录
