**08:python3中列表的知识讲解**
1. append:列表的添加
用法xxx.append()
---------------------
list1=[1,2,0,8,4,6,9]

1. clear:全部清空
用法:
    list1.clear()
    print(list1)
------------------
1. copy:复制
用法:
    list2=list1.copy()
    print(list2)
----------------------------
1. count:在列表中出现了几次
用法:
    print(list1.count(3))
-------------------------------
1. extend:合并
用法:
    list2=['admin','wuya']
    list1.extend(list2)
     print list2
     print list1
--------------------------------
1. index:索引
用法:
    print(list1.index(3))
--------------------------------
1. insert:把元素插入到第几位
用法:
    list1.insert(4,5)
    print(list1)
---------------------------------
1. pop:默认删除最后一位并且把他打印出来
用法:
    print(list1.pop())
    print(list1)
---------------------------------
1. remove:指定要删除的元素
用法:
    list1.remove(6)
    print(list1)
----------------------------------
1. reverse:反转
用法:
    list1.reverse()
    print(list1)
-----------------------------------
1. sort:排序(从小到大)
用法:
    list1.sort()
    print(list1)

-------------------------------------
1.+列表的相加
用法:
	list1=[1,2,3]
	list2=[4,5,6]
	list3=list1+list2  #[1,2,3,4,5,6]
----------------------------------------
1.列表的相乘
用法:
	list1=[1,2,3]
	print(list1*2) #[1,2,3,1,2,3]
--------------------------------------------------------------------------------------------------
1.要查找某个值是否在列表中，可以使用 in 运算符。如果值在列表中出现一次或多次，则返回 True，否则返回 False
用法:
	list1=[1,2,3,4]
	print(2 in list1)
--------------------------------------------------------------------------------------------------
1.要某个值是否不在列表中，可以使用 not 操作符
	print(not 2 in list1)
--------------------------------------------
1.len函数-要获取列表中的项目数量
	print(len(list1))
---------------------------------------------
1.列表的嵌套
list1=[1,2,[3,4,5],6]
-----------------------------------------------

列表推导式(列表应用)
list1=[1,2,3,4,5]
print([i for i in list1 if i>2])