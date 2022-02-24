# populating-list-after-for-loop
l =[1,2,3,4,5,6,7,8,9,10,11,12,13]
k = []
for i in range(len(l)):
    a = l[i]*l[i]
    k.append(a)
    i = i+1
print(k) 
