# Assignment 4: Spike train analysis

In this assignment we will learn the key tools for analysis for spike trains. Spike trains are time-series, and consist of a sequence of irregularly spaced events (spikes=action potentials). In that sense they differ from classical time series such as EEG signals, fMRI or LFP where datapoints are regularly sampled. Because of this difference, a series of tools have been developed to analyze spike trains, which we will cover in this assignment.

The following resources will help you to get ready to complete this assignment. <br>
Watch:
        <li> <a href="https://youtu.be/smHwRzk81b0?t=688" target="_blank">this video</a> (until 1:01'54) from a MIT course by Prof. Michale Fee to learn about key concepts for spike train analysis: the **Poisson process**, **Fano Factor**, **inter-spike intervals**, **cross-correlation** and **auto-correlation**. You do NOT need to follow the equations, just the concepts. </li> 
        <li> <a href="https://youtu.be/m1w7oywzwpA" target="_blank">the first part of this video</a> (until 17'15) to learn about Generalized Linear Models (GLM) and in particular about the **Poisson GLM for spike count regression**. Things get a bit more mathy after 10'12: again, forget about the equations if you cannot follow them and try to focus on the concepts. Remember that we have used GLMs previously: linear regression and logistic regressions are classes of GLMS, for continuous and binary data respectively.</li>

Here is the assignment: [Notebook](Assignment4.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ahyafil/MBC-DataAnalysis/blob/main/A4_SpikeTrainAnalysis/Assignment4.ipynb) 
