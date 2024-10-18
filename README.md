1 Check Button 
from tkinter import *
from tkinter import ttk
r=Tk()
r.title("CHECK BOTTON")
var1=IntVar()
var2=IntVar()
cb=ttk.Checkbutton(r,text="PHP", variable=var1).grid(row=0, column=0)
cb1=ttk.Checkbutton(r,text="PYTHON", variable=var2).grid(row=1, column=0)
r.mainloop()

2 Frame....
from tkinter import *
from tkinter import ttk
r=Tk()
frame = Frame (r)
frame.pack()
bottomframe = Frame (r)
bottomframe.pack(side = BOTTOM)
redbutton=Button(frame,text="red", fg="red")
redbutton.pack(side=LEFT)
greenbutton=Button(frame,text="green", fg="green")
greenbutton.pack(side=LEFT)
bluebutton=Button(frame,text="blue", fg="blue")
bluebutton.pack(side=BOTTOM)
r.mainloop() 

3 two point diagram 
import matplotlib.pyplot as plt
import numpy as np
xpoints=([1, 4, 6, 9])
ypoints=([10, 8, 5, 10])
plt.plot(xpoints, ypoints)
plt.show() 

4 mark circle 
import matplotlib.pyplot as plt
import numpy as np
ypoints=([10, 8, 5, 10])
plt.plot(ypoints, marker="o")
plt.show()
