# Binary_Search
This program will search a number from a given list using a searching technique called binary search.



def binary_search(a,x):
    first_pos=0
    last_pos=len(a)-1
    flag=0  # Element is not yet found
    count=0
    while(first_pos<=last_pos and flag==0):
        count+=1
        mid=(first_pos+last_pos)//2
        if(x==a[mid]):
            flag=1
            print("The element found at pos :",mid)
            print("The no of iterations are:",count)
            return
        else:
            if(x<a[mid]):
                last_pos=mid-1
            else:
                first_pos=mid+1
    if(flag==0):
             print("Element not found")
                
a=[]
for i in range (1,101):
    a.append(i)
binary_search(a,102)    
    
