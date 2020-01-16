bubble sort:
a=[14,33,27,35,10]
def bubble(a):
    k=0
    while k<len(a)-1:
        for i in range(0,len(a)-1):
            if a[i]>a[i+1]:
                a[i],a[i+1]=a[i+1],a[i]
            else:
                pass
        k=k+1
    return a    
            
res=bubble(a);
print(res)
