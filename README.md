
import turtle

window = turtle.Screen()
window.setup(1200, 800)

window.bgcolor('green')
window.screensize(1200, 800)

pen = turtle.Turtle()
for current_x in [-400, -200, 0, 200, 400]:
    pen.setpos(x=current_x, y=0)
    pen.circle(radius=100)
    pen.forward(100)
window.mainloop()
