# 7-3-2022-Assignment-01
l=input().split()

s=[]

for i in l:

    s.append(int(i))

res=[sorted(s).index(x)+1 for x in s]

print(res)
