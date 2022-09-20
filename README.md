from turtle import *

speed(10000)
pensize(5)
bgcolor('cyan')
color('dark blue')
for i in range (75):
	circle(200)
	left(5)
for i in range(75):
	speed(1000)
	color("red")
	circle(150)
	right(5)
for i in range(75):
	speed(1200)
	color("green")
	circle(100)
	left(5)
	
done()