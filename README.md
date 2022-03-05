
l=[]t=[]
n=int(input("Enter the number of elements:"))
for i in range(n):
  x=int(input()) 
l.append(x)
for i in l: 
  if i not in t: 
     t.append(i)
   else: 
         print(i)
