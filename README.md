# Blackjack
h=int(input())
for i in range(h):
    a,b=[int(q) for q in input().split()]
    req=21-a-b
    if req>10:
        print("-1")
    else:
        print(req)
