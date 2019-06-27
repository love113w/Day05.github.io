Day05 craps赌賭博遊戲

2019.06.27 

規則：玩家丟兩個骰子，
如果第一次點數和為7或11，則玩家勝利；
如果點數和為2、3或12，則玩家輸。
若和為其他點數，則記錄第一次點數和，玩家繼續擲骰子，直到點數和為第一次點數和則玩家勝利；若點數和為7則玩家輸。




```py

from random import randint

x = randint(1,6)
y = randint(1,6)

print x+y
print "\n"

if x+y==7 or x+y==11:
    print "gammer win"
elif x+y==2 or x+y==3 or x+y==12:
    print "gammer lose"
else:
    total=x+y
    for i in range(9999999):
        x=randint(1,6)
        y=randint(1,6)
        print x+y
        print "\n"
        if x+y==total:
            print "gammer win"
            break
        elif x+y==7:
            print "gammer lose"
            break
            

```


