**10-python中字典的知识详解**

# 01:字典的关键字dict={"key":value} #

定义的方式
dict={'a':'b','c':4}
dict2={a='wta',b='wiya'}

方法详解:

01:clear-->全部清空
用法:
     dict1.clear()
     print dict1 
02:copy:复制    
用法:
    dict2=dict1.copy()
    print dict2
03:pop删除指定的key对应的value值，并且打印出来
用法:
     print dict1.pop('age')
     print dict1
04:'''判断key是否存在''
用法:
  age=30
  if dict1.has_key('age'):
	if age>18:
		print dict1['age']
   else:
	print 'Sorry,no age key'
05:'获取到字典中key对应的具体value值'''
用法:
     print dict1['age']
     print dict1.get('age')
06:获取到所有的key值
用法:
    for key in dict1.keys():
	print key
07: 获取到所有的vakue值
用法:
    for value in dict1.values():
	print value
08:对字典循环
用法:
    for key,value in dict1.items():	
    print key,':',value

09:使用fromkeys生成新的字典
用法:
    dict1={'name':'wuya','age':10,'address':'xian'}
	字典对象.fromkeys((字典的键),(键对应的值))
  	print(list1.fromkeys(1,2,3),('one','m','sdsds'))
10:update:字典的拓展
用法:
    dict8={"3":3,"4":4}
    dict9={"5":5}
    dict8.update(dict9)
    print(dict8)    

# 02:数据:基于json格式的字符串类型的数据 #
一个标准：
1、业务状态码:code:200
2、消息:msg
3、数据:data

高级用法|:

   dict4={"num1":15,"num2":16}
   print(dict4)
#  sorted()有序的排列
print(sorted(dict4.items(),key=lambda item:item[0]))

