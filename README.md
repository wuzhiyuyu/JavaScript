# JavaScript  
弹出输入框 用户输入**prompt()**  
由prompt输入的值类型都是字符串  
输出**alert()**  
程序员能看到的输出**console.log()**  
  
### 变量  
内存中储存数据的空间  
1. 声明变量：var  
2. 赋值：=  
同时定义多个变量用**，**隔开，*更新变量*  
  
交换两个变量的值，声明一个临时变量temp  
### 简单数据类型  
* 数字型  
* 布尔型（true/false，相加时按照1/0计算）  
```
var flag=true;  
console.log(flag+1);     //2
```
* 字符串  
* 声明了变量但没有给值，此时a=undifined未定义的数据类型  
```
var variable=undifined;  
console.log(variable+'pink');      //undifinedpink 任意类型与字符串相加，输出字符串  
console.log(variable+1);           //NaN 非数值  
```
* Null空值   与数字或布尔相加时看做0
  
NaN非数值  
**isNaN()** 判断非数值，返回true或false  
  
\n转义字符 换行  
  
**length**测量字符长度  
```
var str='my name is andy'  
console.log(str.length)     //15  
```
#### 字符拼接  
**+** 连接，且数值相加，字符相连  
**typeof**检测变量数据类型，null值输出Object  









