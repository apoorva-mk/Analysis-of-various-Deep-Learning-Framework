# Analysis-of-various-Deep-Learning-Frameworks

Contains the performance analysis of various deep learning frameworks such as Tensorflow, Pytorch, Scikit Learn.
A CNN trained on fashion MNIST written in all the above frameworks is used for comparison.
Done as a part of Performance Modelling Project- IT 364

**Steps to obtain heap profiling**

- Install valgrind software
- Save .ipynb as .py file
- run the command valgrind --tool=massif python3 example.py
- Note the process id while it executes ( execution is very slow )
- Heap profile statistics will be stored in massif.out.<pid> 
