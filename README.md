# Regular-expression Notes
### 基本语法
```
[abc]    匹配方括号中的任意一个字符    
[^abc]   匹配方括号中不包含的任意字符
[a-z]    匹配a-z中的任意字符
[a-zA-Z] 匹配a-z或A-Z中的任意字符
[0-9]    匹配任意数字
(abc)    匹配字符串abc
(a|b|c)  匹配a或b或c
{0,1}    匹配前面的子表达式零次或一次，等同于?
{0,}     匹配前面的子表达式零次或多次 ，等同于*
{1,}    匹配前面的子表达式一次或多次，等同于+ 
.       匹配除换行符以外的任意字符
\       转义符，它可以还原元字符原来的含义，允许你匹配保留字符 [ ] ( ) { } . * + ? ^ $ \ |
^       开始符
$       结束符
\s      匹配空格
\S      匹配非空格
\d      匹配任意数字，等同于[0-9]
\D      匹配任意非数字
\w      匹配任意字母数字或下划线
\W      匹配任意非字母数字或下划线
```
### 断言

### 
