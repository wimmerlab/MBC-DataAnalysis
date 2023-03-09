## Assignment 5: Dimensionality reduction

**In this assignment, we will see how to analyze high-dimensional neural data:**
- basics of **principal component analysis (PCA)**
- dimensionality reduction with PCA
- as application, we will use a neural data recorded from monkey prefrontal cortex during a working memory task
- finally, we will decode the memorized cue from the monkey's brain activity 

<div class="alert alert-block alert-warning">
<b>Preparing for this assignment:</b> 

The <a href="https://compneuro.neuromatch.io/tutorials/W1D4_DimensionalityReduction/student/W1D4_Intro.html" target="_blank">material from the Neuromatch Academy Summer School</a> is a great resource if you want to dive deeper into this topic. 
The following resources will help you to get ready to complete this assignment. 
<ul>
    <li>Watch <a href="https://youtube.com/watch?v=zeBFyRaoVnQ" target="_blank">this video</a> (until to 23:15 min) as an introductoin to dimensionality reduction in neuroscience. You will learn that dimensionality reduction is a machine learning technique for transforming data from a high-dimensional space into a lower-dimensional space. In the video, Byron Yu introduces you to the basic concepts of dimensionality reduction and discusses how it is used to investigate the possible underlying low-dimensional structure of neural population activity.
    <li>This <a href="https://youtube.com/watch?v=-f6T9--oM0E" target="_blank">video</a> from the Neuromatch summer school explains the mathematical basis of PCA. If necessary, refresh your knowledge about covariance matrices and eigenvalues (this is not a maths course but it will help you to get a better intuition how PCA works).
        <li>Check out these sites to gain intuition on what PCA is and is used for: 
    <ul>
        <li>https://towardsdatascience.com/a-one-stop-shop-for-principal-component-analysis-5582fb7e0a9c</li>
        <li>https://setosa.io/ev/principal-component-analysis/</li>
    </ul>
</ul>
</div>

- First part: PCA tutorial [Notebook](Assignment5_tutorial.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/wimmerlab/MBC-DataAnalysis/blob/main/A5_DimensionalityReduction/Assignment5_tutorial.ipynb)

- Second part: the assignment [Notebook](Assignment5.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/wimmerlab/MBC-DataAnalysis/blob/main/A5_DimensionalityReduction/Assignment5.ipynb)
