# excel-file-merge-app

# Watch the tutorial video

[How to build a Cryptocurrency Price App in Python using Binance API | Streamlit #28](https://youtu.be/CkcJ9_dpjqw)

<a href="https://youtu.be/xt4hrtG4t3s"><img src="http://img.youtube.com/vi/CkcJ9_dpjqw/0.jpg" alt="How to build a Cryptocurrency Price App in Python using Binance API | Streamlit #28" title="How to build a Cryptocurrency Price App in Python using Binance API | Streamlit #28" width="500" /></a>

# Demo

Launch the web app:

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://share.streamlit.io/dataprofessor/binance/main/app.py)

# Reproducing this web app
To recreate this web app on your own computer, do the following.

### Create conda environment
Firstly, we will create a conda environment called *binance*
```
conda create -n binance python=3.7.9
```
Secondly, we will login to the *excel* environement
```
conda activate binance
```
### Install prerequisite libraries

Download requirements.txt file

```
wget https://raw.githubusercontent.com/dataprofessor/binance/main/requirements.txt

```

Pip install libraries
```
pip install -r requirements.txt
```

###  Download and unzip contents from GitHub repo

Download and unzip contents from https://github.com/dataprofessor/binance/archive/main.zip

###  Launch the app

```
streamlit run app.py
```
