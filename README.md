[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-8d59dc4de5201274e310e4c54b9627a8934c3b88527886e3b421487c677d23eb.svg)](https://classroom.github.com/a/5dx8mdF_)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-c66648af7eb3fe8bc4f294546bfd86ef473780cde1dea487d3c4ff354943c9ae.svg)](https://classroom.github.com/online_ide?assignment_repo_id=10627923&assignment_repo_type=AssignmentRepo)
# Homework 3

This is the template repository for Homework 3 for [BEE 6940, Climate Risk Analysis](https://viveks.me/climate-risk-analysis) at Cornell University, Spring 2023. The goal of this homework is to calibrate a sea-level rise model using Bayesian methods and to compare several point estimates to the probabilistic ensemble.

**If you are registered in the class, DO NOT CLONE THIS REPOSITORY.** Instead, use the GitHub Classroom link from Ed Discussion to create your own repository.

## Learning Objectives

After completing Homework 3, you should be able to:
  * load and work with tabular data (such as `.csv` files);
  * specify priors for model and statistical parameters;
  * use Markov chain Monte Carlo to sample from posterior distributions;
  * find best-fit estimates (maximum *a posteriori* and maximum likelihood) for parameters by optimizing;
  * compare the impacts of point estimates on projections to the use of a full probabilistic ensemble.

## Repository Overview

The repository consists of the following files and folders:
- `hw3.ipynb`: Jupyter Notebook for the homework assignment. Students should create code or Markdown blocks as necessary to answer questions. **This is the only file you should need to edit.**
- `Project.toml`: Julia environment files. These should just work, but feel free to add other packages as needed using the `Pkg` package manager. **This is the only other file that you might end up making changes to, though you should do this using `Pkg`, not directly.**
- `LICENSE`: This material is licensed using the MIT license. You can ignore this for working on the problem set.
- `README.md`: This file. You shouldn't need to touch this.
- `.gitignore`: This tells `git` what files to ignore. You shouldn't need to touch this.
- `data/`: folder containing data files corresponding to historical and RCP 8.5 global mean temperatures as well as historical sea-level rise.
