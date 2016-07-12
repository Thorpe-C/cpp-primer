
##Exercise 4.01
>表达式 5 + 10 * 20 / 2 的求值结果是多少

(5+((10*20)/2)) = 105

##Exercise 4.02
>根据4.12节中的表，在下述表达式的合理位置添加括号，使得添加括号后的运算对象的组合顺序与添加括号前一致

* *vec.begin()          //*(vec.begin())
* *vec.begin() + 1      //(*(vec.begin())) + 1

##Exercise 4.04
>在下面的表达式中添加括号，说明其求值的过程以及结果。编写程序编译表达式输出其结果验证之前的推断。
```cpp
12 / 3 * 4 + 5 * 15 + 24 % 24 / 2 // (((12 / 3) * 4) + (5 * 15) + ((24 % 24) / 2)) = 91
```

##Exercise 4.05
>写出下列表达式的求职结果


* -30 * 3 + 21 / 5 = -86
* -30 + 3 * 21 / 5 = -10
*  30 * 3 + 21 % 5 = 91
* -30 * 3 + 21 % 5 = -89


##Exercise 4.06
>写出一条表达式用于确定一个整数是奇数还是偶数

```cpp
num % 2 == 0 ? "偶数","基数"
```

##Exercise 4.07
>溢出是何含义，请写出三条将导致溢出的表达式

```cpp
unsigned char i = 0 ; i -=1;
unsigned char i = 255 ; ++i;
```
