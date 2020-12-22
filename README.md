
import turtle
import time

window = turtle.Screen()
window.title('snake')
window.setup(500, 500)
window.bgcolor('green')
window.screensize(500, 500)
window.tracer(0)

score = 0
high_score = 0

snake = turtle.Turtle()
snake.color("black")
snake.speed(0)
snake.penup()
snake.goto(0,0)
snake.direction = "stop"

apple =turtle.Turtle()
apple.color("red")
apple.speed(0)
apple.shape("circle")
apple.penup()
apple.goto(0,100)


