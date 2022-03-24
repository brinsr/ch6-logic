# Exercise 2

In this exercise, you'll practice writing conditional statements in Python. In particular, you should complete the following questions on [Codingbat](http://codingbat.com/python), which a website (one of many) for practicing basic programming.

1. [no_teen_sum](http://codingbat.com/prob/p100347)

2. [lucky_sum](http://codingbat.com/prob/p107863)

3. [make_brick](http://codingbat.com/prob/p118406). Note that you may not need to use conditional statements for this, but it's good practice at the kind of logical, abstract thinking used in programming!

Feel free to practice with the other problems as well!
1.def fix_teen(n):
  if((13<=n<=19) and ((n != 15) and (n != 16))) :
    return 0
  else: 
    return n
  
def no_teen_sum(a, b, c):
  return fix_teen(a)+fix_teen(b)+fix_teen(c)  
2.
def lucky_sum(a, b, c):
  if(a==13):
     a=b=c=0
  if(b==13):
     b=c=0
  if(c==13):
    c=0
  return a+b+c
 3.#not solved -will think
def make_bricks(small, big, goal):
  if((((small*1)+(big*5)) == goal) or(small*1 == goal) or(big*5== goal)):
    return True
  else:
    return False
 