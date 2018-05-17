# RepositorioJuego
# juego en clase
from tkinter import *
tk = Tk()
canvas = Canvas(tk, width=400, height=500)
canvas.pack()
def ImagenFondo():

    my_image = PhotoImage(file="Fondo.gif")
    canvas.create_image(0, 0, anchor=NW, image=my_image)
    my_image2 = PhotoImage(file="Goku1.gif")
    canvas.create_image(0, 400, anchor=NW, image=my_image2)
    tk.mainloop()

ImagenFondo()