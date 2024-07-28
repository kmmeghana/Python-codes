# Python-codes
//Ant on a rail
n=int(input())
l=list(map(int,input().spplit()))
pos=0
res=0
for i in l:
pos+=i
if pos==0:
res+=1
print(res)
