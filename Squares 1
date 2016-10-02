# It draws squares of size and spacing following the Fibonacci sequence.
from turtle import *
reset()
up()
goto(-300,0)
down()
def carre(taille):
    c=0
    while c<4:
        forward(taille)
        left(90)
        c=c+1
a=1
b=2
n=int(input("entrez nombre de carrés"))
carre(1)
forward(2)
carre(2)
forward(4)
for i in range(n):
      c=a+b
      a=b
      b=c
      carre(b)
      up()
      forward(2*b)
      down()
