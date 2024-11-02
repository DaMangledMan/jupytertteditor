# Overview

The purpose of this library will be to Create, Edit, and Display Truth Tables of any size. 

I wrote this software because I was searching for something that would simplify the process of creating truth tables, but I was unable to find anything that did something remotely close to what I wanted. In the end I wrote this to streamline the entire process down to a few lines of code.

[Software Demo Video](https://youtu.be/zvBdv4CkKCg)

# Development Environment

I programmed the entire thing inside of VS Code using Python 3.11.9. I also had the Gemini Code Assist extension enabling faster production. I also will be installing and using the following libraries: setuptools, wheel, twine, and multiprocess.

# Useful Websites

- [Python.org : multiprocessing — Process-based parallelism](https://docs.python.org/3/library/multiprocessing.html)
- [Real Python : How to Publish an Open-Source Python Package to PyPI](https://realpython.com/pypi-publish-python-package/)
- [Packaging Python User Guide : Packaging Python Projects](https://packaging.python.org/en/latest/tutorials/packaging-projects/)
- [Youtube : How to Publish a Python Package to PyPI (pip)](https://youtu.be/Kz6IlDCyOUY?si=OIfgLYkwv6yhSrez)

# Future Work

- Currently has functionality to create a truth table of any size, but it is incredibly slow to create them after a certain size is reached considering the nature of truth table length being 2^n possible scenarios (n being the number of vaiables in the truth table). There are plans to add multiprocessing to help speed up the process of creating truth tables.