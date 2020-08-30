**11-python中数据类型的转换**
01:str-list之间的转换 split()
举例:
    str1="9.6"
    str_list=str1.split(",")
    print(str_list)
02:list-str之间的转换 ','.join()
    list1=[1,2,3]
    list_str=",".join(list1)
    print(list_str)
03:dict-list之间的转换  list(xx.keys())
    dict1={"name":"唐飞","age":18}
    list_dict=list(dict1.keys())
    print(list_dict)
04:list-dict之间的转换   dict(enumerate(xx))
    list=[0,1,2,3]
    dict_list=dict(enumerate(list))
    print(dict_list)