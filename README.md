# Python-Temel-Project
www.patika.dev
# 2. Görev
list1 = [[1, 2], [3, 4], [5, 6, 7]]
def ters(x):
    x.reverse()
    for i in range(len(list1)):
        x[i].reverse() 
    return x
a = ters(list1)
print(a)
