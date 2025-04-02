def arr(arr1):
    arr2=[]
    b=1
    for i in arr1:
        while i/10 != 0:
            a=i%10
            b=b*a
            i=i//10
        arr2.append(b)
        b=1
    return arr2

array=[11,22,33,44,55]
result=arr(array)
for i in result:
    print(i, end=' ')
