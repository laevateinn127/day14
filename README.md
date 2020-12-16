# day14
# 引入 tkinter 模組
import tkinter as ff

# 建立主視窗 Frame
window = ff.Tk()#引入函數小tk可改上下都要

# 設定視窗標題
window.title('Hello World')

# 設定視窗大小為 300x100，視窗（左上角）在螢幕上的座標位置為 (250, 150)
window.geometry("300x100+250+150")

# 執行主程式
window.mainloop()
import tkinter as tk

# 自訂函數
def hello():
    print("Hello, world.")

window = tk.Tk()
window.title('Hello World')
window.geometry("300x100+250+150")

# 建立按鈕
button = tk.Button(window,          # 按鈕所在視窗
                   text = 'Hello',  # 顯示文字
                   command = hello) # 按下按鈕所執行的函數

# 以預設方式排版按鈕
button.pack()

window.mainloop()
import tkinter as tk

window = tk.Tk()
window.title('Hello World')
window.geometry("300x100+250+150")

# 標示文字
label = tk.Label(window,                 # 文字標示所在視窗
                 text = 'Hello, world')  # 顯示文字

# 以預設方式排版標示文字
label.pack()

window.mainloop()
import tkinter as tk

window = tk.Tk()
window.title('Hello World')
window.geometry("300x100+250+150")

# 標示文字
label = tk.Label(window,                 # 文字標示所在視窗
                 text = 'Hello, world',  # 顯示文字
                 bg = '#EEBB00',         #  背景顏色
                 font = ('Arial', 12),   # 字型與大小
                 width = 15, height = 2) # 文字標示尺寸   

# 以預設方式排版標示文字
label.pack()

window.mainloop()
import tkinter as tk

window = tk.Tk()
window.title('Hello World')
window.geometry("300x100+250+150")#點後接是函數庫

import tkinter as tk

def onOK():
    # 取得輸入文字
    print("Hello, {}.".format(entry.get()))

window = tk.Tk()
window.title('Hello World')
window.geometry("300x100+250+150")

# 標示文字
label = tk.Label(window, text = '姓名')
label.pack()

# 輸入欄位
entry = tk.Entry(window,     # 輸入欄位所在視窗
                 width = 20) # 輸入欄位的寬度
entry.pack()

# 按鈕
button = tk.Button(window, text = "OK", command = onOK)
button.pack()

window.mainloop()import tkinter as tk

# 引入訊息視窗模組
import tkinter.messagebox

def onOK():
    msg = "Hello, {}.".format(entry.get())
    tkinter.messagebox.showinfo(title = 'Hello', # 視窗標題
                                message = msg)   # 訊息內容

window = tk.Tk()
window.title('Hello World')
window.geometry("300x100+250+150")

# 標示文字
label = tk.Label(window, text = '姓名')
label.pack()

# 輸入欄位
entry = tk.Entry(window, width = 20)
entry.pack()

# 按鈕
button = tk.Button(window, text = "OK", command = onOK)
button.pack()

window.mainloop()
https://officeguide.cc/python-tkinter-gui-tcl-tk-interface-tutorial-examples/:視窗
https://www.toodoo.com/db/color.html:色碼表
https://docs.python.org/zh-tw/3/tutorial/index.html:python
```
def:定義
```
https://stackoverflow.com/questions/23904274/is-there-a-way-to-get-colored-text-in-githubflavored-markdown/41043795#41043795

