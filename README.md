# Patika--Python-E-itim-Sonu-Proje
##Flatten Function

def flatten(a):
    for x in a:
        if isinstance(x,list):
            flatten(x)
        else:
            new_list.append(x)

a = ["a",3,7,["nasi","oyle",2],8,9,[[5]]]
new_list = []
flatten(a)
print(new_list)

##List Reverse

list=[[1,2],[3,4],[5,6,7]]
list.reverse()
l
[[5, 6, 7], [3, 4], [1, 2]]
for i in list:
  i.reverse()
print(l)  
[[7, 6, 5], [4, 3], [2, 1]]
