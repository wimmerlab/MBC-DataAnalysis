## Assignment 1: descriptive statistics, parametric vs non-parametric methods & linear regression
In this assignment, we will see:
- how to visually inspect experimental data
- how to characterize experimental data using descriptive statistics
- how to perform a simple statistic test using either a parametric (T-test) or non-parametric (shuffling) method
- how to assess the impact of an experimental factor on our experimental measurement using linear regression
- how to take into account the hetereogeneity of our sample population using linear mixed models

<div class="alert alert-block alert-warning">
<b>Preparing for this assignment:</b> 

The following resources will help you to get ready to complete this assignment. 
<ul>
    <li>Watch <a href="http://youtu.be/5q-Ws4y8JE4" target="_blank">this video</a> (here the <a href="https://www.cmrr.umn.edu/~kendrick/statsmatlab/StatsLecture2Slides_Hypothesis.pdf" target="_blank">slides</a>) only until time stamp 23:08 (stop right after permutation tests) in order to learn about:</li>
    <ul>
        <li>the logic of t-tests to test the hypothesis that two samples have the same mean</li>
        <li>the non-parametric equivalent in permutation tests. Make sure you understand this logic</li>
    </ul>
    <li>Watch <a href="https://www.youtube.com/watch?v=KsVBBJRb9TE" target="_blank">this video</a> and then follow with <a href="https://www.youtube.com/watch?v=xIDjj6ZyFuw" target="_blank">this video</a> to learn the concepts about simple linear regression</li>
    <li>For a complementary look on linear regression that put its into the more general framework of model fitting, watch <a href="https://www.youtube.com/watch?v=9JfXKmVB6qc" target="_blank">this video</a> (until 15:10) and then follow with <a href="https://www.youtube.com/watch?v=HumajfjJ37E" target="_blank">this video</a> (linear regression by minimizing squared errors) and <a href="https://www.youtube.com/watch?v=8mpNmzLKNfU" target="_blank">this one</a> (linear regression by maximizing likelihood). These are parts of the material for Model Fitting day which are accessible <a href="https://compneuro.neuromatch.io/tutorials/W1D2_ModelFitting/chapter_title.html" target="_blank">here</a>. </li>
    <li> (Very optional) See <a href="https://www.cns.nyu.edu/~eero/NOTES/leastSquares.pdf" target="_blank">these notes</a> from Eero Simoncelli (NYU) if you want to delve more into the mathematics related to linear regression</li>
    <li>Read <a href="https://doi.org/10.1152/jn.00362.2015" target="_blank">this paper</a> (focussing on Experiment 2) to understand the logic of the experimental data that we will analyze</li>
</ul>
</div>

- First part: descriptive statistics and hypothesis tests [Notebook](A1_LinearRegression/Assignment1A.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/wimmerlab/MBC-DataAnalysis/blob/main/A1_LinearRegression/Assignment1A.ipynb) Solution: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/wimmerlab/MBC-DataAnalysis/blob/main/A1_LinearRegression/Assignment1A_solutions.ipynb)

- Second part: linear regression [Notebook](A1_LinearRegression/Assignment1B.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/wimmerlab/MBC-DataAnalysis/blob/main/A1_LinearRegression/Assignment1B.ipynb) Solution: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/wimmerlab/MBC-DataAnalysis/blob/main/A1_LinearRegression/Assignment1B_solutions.ipynb)
