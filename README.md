# Statistics for AI course

This is the material used for my activities within the 2025 Stats for AI course within UPV/EHU's [Applied Artificial Intelligence and its Mathematical Foundations](https://www.ehu.eus/en/web/graduondokoak/university-specialisation-applied-artificial-intelligence-mathematical-foundations)

## Sitting on the shoulders of giants

This course is nothing but my attempt to communicate concepts and topics that I have learned from many experts, so kudos to them, and my strongest encouragement to read/learn from them

### Books

- ["Probabilistic machine learning": a book series by Kevin Murphy](https://github.com/probml/pml-book)

- [Christopher M. Bishopi. "Pattern recognition and machine learning". Springer, 2006.](https://www.microsoft.com/en-us/research/wp-content/uploads/2006/01/Bishop-Pattern-Recognition-and-Machine-Learning-2006.pdf)

### Courses

- ["Foundations of Graphical Models" by David Blei](https://www.cs.columbia.edu/~blei/fogm/2020F/index.html)

- ["Stat 406: Methods for Statistical Learning" by Geoff Pleiss and Trevor Campbell](https://ubc-stat.github.io/stat-406/schedule/)

- ["Probabilistic Machine Learning" by Carl Edward Rasmussen](https://mlg.eng.cam.ac.uk/teaching/4f13/2425/)

- ["Advanced Probabilistic Machine Learning and Applications (2022)" by Caterina De Bacco](https://github.com/APMLA-2021/)

## Practice labs

- The [labs](./labs) directory contains the notebooks for the practice sessions of the course.
- The [labs_full](./labs_full) directory contains the full notebooks, with my attempt to the practice sessions of the course.

### Conda environment for notebooks

- The environment that I have used to design and solve the practice sessions can be created and replicated as follows

```bash
$ conda create -n 2025_stats_for_ai python=3.13 
$ conda activate 2025_stats_for_ai
$ conda install pip 
$ pip install numpy scipy matplotlib jupyter scikit-learn
```
