# Campinas state university (UNICAMP) salaries

[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)
[![Made withJupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter)](https://jupyter.org/try)

![Main graph](https://github.com/Pedronagy/Unicamp_salaries/blob/main/Figures/salaries.jpeg)

## Table of contents
- [Introduction](#introduction)
- [Workflow](#workflow)
    - [Get the data](#get-the-data)
    - [Analyzing the results](#analyzing-the-results)
- [Conclusions](#conclusions)
    - [Main conclusion](#main-conclusion)

## Introduction
This is a project of mine to analyse the UNICAMP university salaries.  
Since its a public institute there is a transparency movement to open to the society the governamental expenses.  
Our main questions with this project are: **Where are the biggest expenses with salaries on the university? Which department? Which people?** and **Are they "normal" or there are anything suspicious?**

## Workflow  
### Get the data
I initially got the data from a site by the university itself called [Portal transparência Unicamp](https://transparencia.unicamp.br/paginas/consultar-salarios-do-mes-atual/ "Portal transparência").
The data itself is very clean and organized (congratulations Unicamp, you are a special one) so is only requires some transformation and digit cleaning (like the money sign $).

### Analyzing the results
In the file ([Analisys.ipynb](https://github.com/Pedronagy/Unicamp_salaries/blob/main/Analisys.ipynb)) all the analysis is done. More details can be seen there.

## Conclusions
1. There are very few super salaries (only 11) on the university.  
2. The highest salaries are usually of professors.With the acually biggest being from attorneys.  
3. The biggest expenses with salaries are usually departments less focused on research.  
4. The biggest mean salaries are usually from colleges.  
### Main conclusion
There is no suspicious distribution or expenses that i could find and the differences in salaries and departments made sense. Which is a good thing.  
No one wants a corrupt university, after all :)
