Day05 craps赌賭博遊戲

### 2019.06.27 


```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3
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
            
print "Hello World!\n"

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).


