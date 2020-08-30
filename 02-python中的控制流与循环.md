# 06:python中的控制流与循环 #
**01:if语句**
基本格式:
		if xxx:
		  print()
-----------------------
        if xxx:
           print()
        else
		   print()
-------------------------
        if  xxx:
           print()
        elif xxx:
           print()
        else:
           print()
---------------------------
**# 02:True #**
a = True
*#当条件为真的的时候if语句后面不需要跟条件*
if a:
    print()
else:
    print()
-----------------------------------------
# 03:for循环 #
基本格式:
		for x in xxx:
		   print()
举例:
        for i in range(0,10):
		   print(i)
----------------------------------------
# 04:while True #
举例:
	while True:
	   p = int(input("1,姓名 2,年龄\n"))
       if p ==1:
           name = input("你的姓名是什么?\n")
       elif p ==2:
           age = input("你的年龄多少:")
       else:
            break
------------------------------------------
# 05:三目运算符 #  
举例说明:

age= 25

print("成功") if age>25 else print("失败")
-------------------------------------------
num=20
if num>20:print("成功")
--------------------------------------------
### **while循环的使用说明** ###
while 循环语法：重复使用
break 关键字使用：结束当前的循环
Continue 关键字使用：跳过本次循环，继续下一次循环
无限循环是一种特殊的 while 循环;它永远不会停止运行。它的条件总是 True,您可以通过使用 Ctrl-C 快捷键或关闭程序来停止程序的执行