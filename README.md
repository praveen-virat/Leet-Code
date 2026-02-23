num=eval(input("enter a list:"))
l=len(num);
key=int(input("enter a key:"))
k=0
print("[",end="")
for i in range(l):
   if num[i]!=key:
      k=k+1
      print(num[i],end=",")
   else:
      continue
for j in range(l-k):
   print("_",end=",")
print("]")
print(k)
