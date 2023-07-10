# GoldMining
# cook your dish here
t=int(input())
while t:
    n,x,y=map(int,input().split())
    if((y*(n+1))>=x):
        print("Yes")
    else:
        print("No")
    t-=1
