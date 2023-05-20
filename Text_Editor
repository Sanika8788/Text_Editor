# Text_Editor
from tkinter import *

root = Tk()
root.geometry("350x250")
root.title("Text Editor")
root.minsize(height=450, width=650)
root.maxsize(height=650, width=750)


# adding scrollbar
scrollbar = Scrollbar(root)

# packing scrollbar
scrollbar.pack(side=RIGHT,fill=Y)


text_info = Text(root,
				yscrollcommand=scrollbar.set)
text_info.pack(fill=BOTH)

# configuring the scrollbar
scrollbar.config(command=text_info.yview)

root.mainloop()
