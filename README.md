# Python-import-turtle-Advance-Art-106
Create python use import turtle graphics code
from turtle import*
from time import*
import colorsys
title("Satyam Shorrf")
bgcolor("black")
tracer(90)
pensize(2)
h = 0.3
sleep(2)
for i in range(1100):
    c = colorsys.hsv_to_rgb(h,1,1)
    h += 0.005
    color(c)
    penup()
    goto(0, 0)
    circle(12, 50)
    forward(20)
    pendown()
    right(360)
    fillcolor(c)
    begin_fill()
    circle(10, 320)
    end_fill()
    backward(i/4)
    right(6)
draw()    
done()    
