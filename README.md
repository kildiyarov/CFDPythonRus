
# CFD Python

> Please cite as: Barba, Lorena A., and Forsyth, Gilbert F. (2018). CFD Python: the 12 steps to Navier-Stokes equations. _Journal of Open Source Education_, **1**(9), 21, https://doi.org/10.21105/jose.00021

[![DOI](https://jose.theoj.org/papers/10.21105/jose.00021/status.svg)](https://doi.org/10.21105/jose.00021)

**CFD Python** или **12 шагов до уравнений Навье-Стокса** — это практический модуль для изучения основ вычислительной гидродинамики (CFD) путем кодирования решений основных дифференциальных уравнений в частных производных, описывающих физику течения жидкости.
Модуль был частью курса, который читал [Prof. Lorena Barba](http://lorenabarba.com) с 2009 по 2013 год на факультете машиностроения Бостонского университета (с тех пор профессор Барба перешел в Университет Джорджа Вашингтона).

Модуль предполагает только базовые знания программирования (на любом языке) и некоторый опыт работы с дифференциальными уравнениями в частных производных и гидромеханикой. «Шаги» были вдохновлены идеями доктора Рио Йокоты, который до 2011 года был постдоком в лаборатории профессора Барбы, а уроки были усовершенствованы профессором Барбой и ее студентами в течение нескольких семестров, преподававших курс CFD.
Мы написали этот набор блокнотов Jupyter в 2013 году для проведения интенсивного двухдневного курса в Мендосе, Аргентина.

Проводя учащихся по этим шагам (не пропуская ни одного!), они получают много ценных уроков. Постепенный характер упражнений означает, что они получают чувство достижения в конце каждого задания, и они чувствуют, что учатся с минимальными усилиями. По мере продвижения они, естественно, практикуют повторное использование кода и постепенно изучают методы программирования и построения графиков. Анализируя свои результаты, они узнают о числовой диффузии, точности и сходимости.

## Как использовать этот модуль

На обычном университетском курсе студенты могут пройти уроки **CFD Python** за 4–5 недель.
В качестве интенсивного учебного модуля модуль может быть пройден за два или три полных дня, в зависимости от предыдущего опыта учащегося. 
Во всех случаях учащиеся должны следовать рабочим примерам в каждом уроке, повторно набирая код в новом блокноте Jupyter, возможно, делая оригинальные заметки по мере того, как они пробуют что-то.

Lessons
-------
> Launch an interactive session with this module using the Binder service:
[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/barbagroup/CFDPython/master)

Steps 1–4 are in one spatial dimension. Steps 5–10 are in two dimensions (2D). Steps 11–12 solve the Navier-Stokes equation in 2D. Three "bonus" notebooks cover the CFL condition for numerical stability, array operations with NumPy, and defining functions in Python.

* [Quick Python Intro](http://nbviewer.jupyter.org/github/barbagroup/CFDPython/blob/master/lessons/00_Quick_Python_Intro.ipynb)
—For Python novices, this lesson introduces the numerical libraries (NumPy and Matplotlib), Python variables, use of whitespace, and slicing arrays.
* [Step 1](http://nbviewer.jupyter.org/github/barbagroup/CFDPython/blob/master/lessons/01_Step_1.ipynb)
—Linear convection with a step-function initial condition (IC) and appropriate boundary conditions (BCs).
* [Step 2](http://nbviewer.jupyter.org/github/barbagroup/CFDPython/blob/master/lessons/02_Step_2.ipynb)
—With the same IC/BCs, _nonlinear_ convection.
* [CFL Condition](http://nbviewer.jupyter.org/github/barbagroup/CFDPython/blob/master/lessons/03_CFL_Condition.ipynb)
—Exploring numerical stability and the Courant-Friedrichs-Lewy (CFL) condition.
* [Step 3](http://nbviewer.jupyter.org/github/barbagroup/CFDPython/blob/master/lessons/04_Step_3.ipynb)
—With the same IC/BCs, _diffusion_ only.
* [Step 4](http://nbviewer.jupyter.org/github/barbagroup/CFDPython/blob/master/lessons/05_Step_4.ipynb)
—Burgers’ equation, with a saw-tooth IC and periodic BCs (with an introduction to Sympy).
* [Array Operations with NumPy](http://nbviewer.jupyter.org/github/barbagroup/CFDPython/blob/master/lessons/06_Array_Operations_with_NumPy.ipynb)
* [Step 5](http://nbviewer.jupyter.org/github/barbagroup/CFDPython/blob/master/lessons/07_Step_5.ipynb)
—Linear convection in 2D with a square-function IC and appropriate BCs.
* [Step 6](http://nbviewer.jupyter.org/github/barbagroup/CFDPython/blob/master/lessons/08_Step_6.ipynb)
—With the same IC/BCs, _nonlinear_ convection in 2D.
* [Step 7](http://nbviewer.jupyter.org/github/barbagroup/CFDPython/blob/master/lessons/09_Step_7.ipynb)
—With the same IC/BCs, _diffusion_ in 2D.
* [Step 8](http://nbviewer.jupyter.org/github/barbagroup/CFDPython/blob/master/lessons/10_Step_8.ipynb)
—Burgers’ equation in 2D
* [Defining Functions in Python](http://nbviewer.jupyter.org/github/barbagroup/CFDPython/blob/master/lessons/11_Defining_Function_in_Python.ipynb)
* [Step 9](http://nbviewer.jupyter.org/github/barbagroup/CFDPython/blob/master/lessons/12_Step_9.ipynb)
—Laplace equation with zero IC and both Neumann and Dirichlet BCs.
* [Step 10](http://nbviewer.jupyter.org/github/barbagroup/CFDPython/blob/master/lessons/13_Step_10.ipynb)
—Poisson equation in 2D.
* [Step 11](http://nbviewer.jupyter.org/github/barbagroup/CFDPython/blob/master/lessons/14_Step_11.ipynb)
—Solves the Navier-Stokes equation for 2D cavity flow.
* [Step 12](http://nbviewer.jupyter.org/github/barbagroup/CFDPython/blob/master/lessons/15_Step_12.ipynb)
—Solves the Navier-Stokes equation for 2D channel flow.




## Dependencies

To use these lessons, you need Python 3, and the standard stack of scientific Python: NumPy, Matplotlib, SciPy, Sympy. And of course, you need [Jupyter](http://jupyter.org)—an interactive computational environment that runs on a web browser.

This mini-course is built as a set of [Jupyter notebooks](https://jupyter-notebook.readthedocs.org/en/latest/notebook.html) containing the written materials and worked-out solutions on Python code. To work with the material, we recommend that you start each lesson with a fresh new notebook, and follow along, typing each line of code (don't copy-and-paste!), and exploring by changing parameters and seeing what happens. 


<details>
  <summary> Installing via Anaconda </summary>
  <br>
We *highly* recommend that you install the [Anaconda Python Distribution](http://docs.continuum.io/anaconda/install). It will make your life so much easier. 
You can download and install Anaconda on Windows, OSX and Linux. 

After installing, to ensure that your packages are up to date, run the following commands in a terminal:

```Bash
conda update conda
conda update jupyter numpy sympy scipy matplotlib
```

If you prefer Miniconda (a mini version of Anaconda that saves you disk space), install all the necessary libraries to follow this course by running the following commands in a terminal:

```Bash
conda update conda
conda install jupyter
conda install numpy scipy sympy matplotlib
```
</details>

<details>
  <summary> Without Anaconda </summary>
  <br>
If you already have Python installed on your machine, you can install Jupyter using pip:

```Bash
pip install jupyter
```

Please also make sure that you have the necessary libraries installed by running

```Bash
pip install numpy scipy sympy matplotlib
```
</details>



## How to contribute to CFD Python

We accept contributions via pull request—in fact, several users have already submitted pull requests making corrections or small improvements. You can also open an issue if you find a bug, or have a suggestion. 

## Copyright and License

(c) 2017 Lorena A. Barba, Gilbert F. Forsyth. All content is under Creative Commons Attribution [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/legalcode.txt), and all [code is under BSD-3 clause](https://github.com/engineersCode/EngComp/blob/master/LICENSE) (previously under MIT, and changed on March 8, 2018). 

We are happy if you re-use the content in any way!

[![License](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause) [![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

