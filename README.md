# Python-Temel-Project
www.patika.dev
# 1. Görev
```
list1 = [[1,'a',['cat'],2],[[[3]],'dog'],4,5]
def flat(x):
    list2 = []
    for i in x:
        if type(i) is list:
            for j in i:
                if type(j) is list:
                    for k in j:
                        if type(k) is list:
                            for h in k:
                                list2.append(h)
                        else:
                            list2.append(k)
                else:
                    list2.append(j)        
        else:
            list2.append(i)
    return list2
print(flat(list1))
```
# 2. Görev
```
list1 = [[1, 2], [3, 4], [5, 6, 7]]
def ters(x):
    x.reverse()
    for i in range(len(list1)):
        x[i].reverse() 
    return x
a = ters(list1)
print(a)

