# RusInflector
Python that can decline and conjugate Russian words
Uses the pymorphy2 library to accomplish everything. All this does is simple input/output and printing.


# Installation
Windows:
Install python 3 from here if you haven't already (you would know if you had): https://www.python.org/ftp/python/3.6.3/python-3.6.3-amd64.exe

Select custom installation and uncheck the development environment option (unless you want to get into python). Make sure that the pip option is checked

Then we install the needed library. 
Open command prompt by typing "cmd" in the start menu. From there type:
> pip install pymorphy2

Then download the zip form the "clone/download" button on this page. Unzip it and run RusInflector by clicking "main.py". Thats it!

Mac:
Python should already be installed on macs but you still need the library, and we need pip to install that. If you don't know what pip is, it isn't installed, so you need the next step.
Open the applications folder then the utilities folder in finder. From there, run terminal.
In terminal type: 
>sudo easy_install pip

Then to install the library, type in terminal:
>pip install pymorphy2

Then download the zip form the "clone/download" button on this page. Unzip it and find the folder that has "main.py"

To run the program, you will need change the directory of your terminal to the location of "main.py".

For example, if "main.py" is on your desktop, type in terminal:
>cd Desktop/

Then to run the program type:
>python main.py

And that should be it??? I don't actually have a mac to test this on. I could also write a bash script to simplify this...

Linux:
If you have linux, you probably don't need as in depth installation as above.
I used pip3, but if you know how to use pip to python3 thats up to you.
Either:
>sudo apt install python3-pip

>pip3 install pymorhpy2

or whatever you do for pip and python3.

Then run main.py with:
>python3 main.py
