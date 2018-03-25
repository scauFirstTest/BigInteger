# BigInteger
==
问题描述
--
创建一个大整数类HugeInteger，该类用一个40个元素的数组来存放一个大整数（最多不超过40位）。
构造函数原型：
HugeInteger(String);
（1）定义几个大整数算术运算的成员函数，包括input、output、add和sub,
add, sub的函数原型为 HugeInteger operation(HugeInteger)
input的函数原型为 void input(String) 功能是改变大数的值为String的值。
output的函数原型为void output()  功能是将大数输出,即打印到屏幕上。
（2）定义几个大整数关系运算的成员函数，包括isEqualTo、isNotEqualTo、isGreaterThan、isLessThan、isGreaterThanOrEqualTo和isLessThanOrEqualTo。每个函数的返回值为布尔类型。
 
函数原型为 boolean operation(HugeInteger)
 
注意:  
1.         大数运算需要考虑到正负，使用单独的变量存储符号位。
2.         大数的输入: 正数形式为”12345”，负数形式为”-123456”
3.         如果运算溢出，截取低40位结果。
4.         包名hugeinteger 中i为小写，类名HugeInteger中I为大写。
