# 代码规范性
1 空格：在include后加空格  
```
#include <stdio.h>
```
前面推荐用四个空格代替Tab键（不同的公司要求不一样）  
2 大括号：有些时候if语句只有一句话，好多人就不写大括号，最好是只要有内容就写大括号，以后再添加语句的时候不容易发生错误  
3 符号位加减乘除等号两边加空格，增强代码可读性，看起来更工整  
```
a = b + c;
```
4 变量名尽量用英文单词或者英文单词的缩写，避免用a,b这种简单的名字  
常用的名字：  
sum 和  
product 积  
temporary 临时的值->tmp    
flag 标识->flg  
statistic 统计（一般用在数组里）->stat  
count 计数  
increment 加1  
decrement 减1  
message 消息 -> msg  
value 值 -> val  
array 数组 -> arr  
position 位置 -> pos,idx(index)  
加 addition -> add  
减 subtraction -> sub  
乘 multiplication -> mul  
除 divide -> div  
取余数 modulus -> mod  
max 最大值  
min 最小值  
5 创建函数，函数名称  
```
//列出所有质数
void list_primes()
{

}
```
```
//查找出最大值的位置
int find_max_pos(int arr[], int n)
{

}
```
6 注释  
比较规范的注释一般都写在长一些的代码段的上方  
```
/**
* 在数组中查找出最大值的位置.
* @param arr 一个数组.
* @param n   数组的长度.
* @return    最大值的下标.
*/
int find_max_pos(int arr[], int n)
{

}
```
