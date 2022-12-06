# Repository4
n=int(input("ENTER THE NUMBER OF TERMS:"))
a=0
b=1
count=0
if(n<=0):
 print('ENTER THE POSITIVE NUMBER')
elif(n==1):
    print("FIBONACCISERIES UPTO",n,":")
    print(a)
else:
        print("FIBONACCISERIES:")
        while(count<n):
          print(a)
          nth=a+b
          a=b
          b=nth
          count+=1
