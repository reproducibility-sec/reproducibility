# "Get in Researchers; We're Measuring Reproducibility": A Reproducibility Study of Machine Learning Papers in Tier 1 Security Conferences
Official implementation of paper: *"Get in Researchers; We're Measuring Reproducibility": A Reproducibility Study of Machine Learning Papers in Tier 1 Security Conferences*
We use Python 3.9.17 to make our figures.
Currently have deployment for python script and Jupyter notebook. We are working on providing a Docker container to assist this and provide easier reproducibility. 
Our data is in *sheet1.csv*, and *figure.py* and *figures-from-paper.ipynb* will generate all of the figures in our paper with the format *Figure[num].pdf* in 
the working directory.
# Requirements
<pre><code>
ipykernel==5.4.3
ipython==7.19.0
ipython-genutils==0.2.0
ipywidgets==7.6.3
jupyter==1.0.0
jupyter-client==6.1.11
jupyter-console==6.2.0
jupyter-core==4.7.0
jupyterlab-pygments==0.1.2
jupyterlab-widgets==1.0.0
keras==2.11.0
Keras-Preprocessing==1.1.2
matplotlib==3.3.3
notebook==6.2.0
numpy==1.19.5
packaging==20.8
pandas==1.2.0
scipy==1.6.0
seaborn==0.11.1
</code></pre>
# Data
We provide our full, collected dataset for reproducing our experiments in *sheet1.csv*.
To recreat Figure 8, we collected new data from USENIX and the awarded badges. This
data is in *artifact.csv*.
# Steps to Reproduce
1. Install requirements: 
<pre><code> pip install -r requirements.txt </code></pre>
2. Download data *sheet1.csv*, *artifact.csv*, *figure.py*, and Jupyter Notebook *figures-from-paper.ipynb* into the same directory, for example:
<pre><code> git clone https://github.com/reproducibility-sec/reproducibility.git </code></pre>
3. [Jupyter Notebook] Start a Jupyter Notebook session with <code>jupyter notebook</code>. Select *figure-from-paper.ipynb*. Run each cell.
3. [Python] Run *figure.py*.
# Citation

