**09:python中元祖知识的讲解**
01:元祖的关键字tuple
示范:
tuple=()
说明:
    1:元祖是不可变的
    2:元祖里面的对象可以改变
    3.通过索引来访问
常用的方法: count index

tuple1=(1,2,3,4,3,[1,2,3],{'name':'wuya'})

    print tuple1.count(3) #count-->元素在元组中出现的次数
    print tuple1.index(4) #index-->元素在元组中的索引
    tuple1[5].insert(3,4)#把元组中的列表由[1,2,3]修改为[1,2,3,4]
    tuple1[6]['name']='weike'#把元组中的字典name修改为weike

举例说明:

tuple1=(1,2,3,"admin",["wuya","18"],{"name":name,"age":18})   
#改变元祖中的内容
tuple1[4][0]="tangfei"
print(tuple1[4][0]) #tangfei
tuple1[5]["name"]="zhangfei"
print(tuple1[5]["name"])#zhangfei



