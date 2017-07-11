# 变量

## 声明

变量名只能包含字母、数字和下划线，但是必须使用字母或下划线开头。

C 语言的变量，必须先声明后使用。声明的时候，必须把变量的类型告诉编译器。

```c
int height;
```

上面代码将变量`height`，声明为`int`类型。

如果几个变量具有相同类型，可以将它们的声明合并。

```c
int height, width;
```

注意，声明变量的语句必须以分号结尾。

## 赋值

变量通过赋值的方式获得值。

```c
height = 8;
```

上面的代码将变量`height`赋值为`8`。

如果变量为`float`类型，赋值时要带上小数点。而且，小数点后面最好还要加上`f`，告诉编译器该变量为`float`类型。

```c
height = 2.83f;
```

可以在声明变量的同时，对该变量进行赋值。

```c
int height = 8;
```

同一个声明语句中，可以对多个变量进行赋值。

```c
int height = 8, width = 10;
```

也可以对一些变量赋值，另一些变量不赋值。

```c
int height = 8, width;
```