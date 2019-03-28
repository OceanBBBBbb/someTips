# someTips
记录一些开发中可以去使用的小东西
主要针对java吧。

    因为有时候发现，有一些编程中想要用到的东西，可能因为不是很好如何根据要求去找，
    或者因为自己接触面和知识点的局限，不知道那些东西，所以可以在遇到了以后简单记录一下。
    毕竟`闻道有先后`，编程语言也是一门语言，重在积累。

## BindingResult

BindingResult可以用来在controller层校验传入的逐个参数值，结合@Valid和@NotBlank(message = "密码不能为空！")做非空判断等。
可以用这个[小教程](https://blog.csdn.net/FU250/article/details/80247930)直接使用。
