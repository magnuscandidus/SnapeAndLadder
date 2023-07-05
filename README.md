# SnapeAndLadder
# cook your dish here
t=int(input())
while t:
    b,ls=map(int,input().split())
    print((((ls**2)-(b**2))**0.5),((ls**2)+(b**2))**0.5)
    t-=1
