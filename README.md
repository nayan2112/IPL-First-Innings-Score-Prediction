# IPL-First-Innings-Score-Prediction
IPL First innings score predictor, a machine learning web app created with Flask on Heroku platform.

## Table of Content
  * [Demo](#demo)
  * [Overview](#overview)
  * [Motivation](#motivation)
  * [Technical Aspect](#Technical-Aspect)
  * [Installation](#installation)
  * [Deployement on Heroku](#deployement-on-heroku)
  * [Directory Tree](#directory-tree)
  * [Technologies used](#technologies-used)
  * [Bug / Feature Request](#bug---feature-request)
  * [Future scope of project](#future-scope)
  * [Credits](#credits)

## Overview
This is a flask web app which predicts the first inning score of Indian Premier League(IPL) with the help of Rgeressor model. The dataset is taken from https://github.com/codophobia/CricketScorePredictor credits to Shivam Mitra. It contains the score made on each ball of the matches played in IPL from 2008 to 2017.

## Motivation
Since childhood I am a great cricket fan. I played cricket at district and state level. Unfortunately 2020 is not a great year for all of us. We can't go outside from our home and enjoy the outdoor games. Last Year, I have started learning Data Science and Machine Learning course from online platform. So I thought to utilize this lockdown period to build something for a cricket fans using AI/ML. It is just a small initiative towards this.

## Technical Aspect:
This project is divided into two parts:
1) Trained a Machine Learning model using Regressor Models(Code is available in this repo).
2) Deployed the model using Flask on Heroku Platform.

## Installation
The Code is written in Python 3.6.10. If you don't have Python installed you can find it [here](https://www.python.org/downloads/). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after [cloning](https://www.howtogeek.com/451360/how-to-clone-a-github-repository/) the repository:
```bash
pip install -r requirements.txt
```

