# AlmeriaVB
This repository contains slides and Jupyter notebooks for VB course in Almeria in Oct 2018. 

# Update: jupyter problems
These are two commands that **might** solve the problems people had with jupyter (try the first one first, then if that does not solve it, the second afterwards):

```
python3 -m pip install --upgrade ipykernel
python3 -m pip install 'ipykernel<5.0.0'

For mac users you may have to do `sudo` ...



The slides (in the `Slides` folder) are named with the lecture number (1 to 5).

The `Python` folder contains the Jupyter notebooks ([More about Jupyter](http://jupyter.org/index.html)) for the code tasks that will be solved in class. These are **unfinished** code examples, hence will not run before "fixed". What to do to fix them will be discussed in class. 

All Python notebooks are developed using Python 3.6 (3.x required). You are expected to bring your own computer with Python installed ([download](https://python.org/download)). Some knowledge about Python is beneficial, but I'll try to walk you through it the best I can.

We use the following packages:
* `jupyter`
* `numpy`
* `scipy`
* `matplotlib`

You can "pip-install"-them using 
```
python3 -m pip install --upgrade pip
python3 -m pip install <packagename>
```

When everything is installed, you should be able to run `jupyter notebook`in the terminal/from the command-line, which would open a file-picker in your favourite browser. Go to the `Python`folder and choose one of the notebooks there. You should see some explanation and some cells of code if everything works. 
