# A short introduction to Machine Learning

This repository contains my personal notes about the course Introduction to Machine Learning of University of Trento.

## Contents

### Part One: Basics

- Introduction
- Data, Features, Models
- Generalization error, Models, Hypothesis space

### Part Two: Supervised Learning

- k-Nearest Neighbor
- Linear Models
- Decision Trees
- Multiclass Classification
- Gradient Descent
- Regularization
- Support Vector Machines
- Ranking
- Neural Networks

### Part Three: Unsupervised Learning

- Unsupervised Learning
- Clustering
- Deep Generative Models

### Part Four: Reinforcement Learning

- Reinforcement Learning

## Structure

All the utils of the project are collected into the principal file, called [ml.pdf](ml.pdf). The folders are organized as follows:

- [chapters](chapters/) contains the .tex file for each chapter.
  - In each chapter there is a final part that contains exercises, open questions, the questions that contains the '!' symbol are the ones that have been asked in the previous exams.
- [img](img/) contains all the images files of the project.

## Usage

In order to compile the latex document into your machine, clone the repository, go to the the clone directory and run the command

```bash
pdflatex ml
```

## Error reports

In order to report some errors in the notes, please open an issue specifying the chapter, the section, and the kind of error; or provide your own correction in a new pull request.
