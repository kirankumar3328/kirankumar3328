from tkinter import *
from tkinter import ttk
r=Tk()
r.title("CHECK BOTTON")
var1=IntVar()
var2=IntVar()
cb=ttk.Checkbutton(r,text="PHP", variable=var1).grid(row=0, column=0)
cb1=ttk.Checkbutton(r,text="PYTHON", variable=var2).grid(row=1, column=0)
r.mainloop()
