<h1 align="center">
  Boggle
</h1>
<p align="center">
  <img src="https://img.shields.io/badge/Python-blue">
  <img src="https://img.shields.io/badge/Flask-pink">
</p>

## Description

In this project I coded a Boggle game Javascript, Python & Flask. The goal of the game is to get the highest point total. To gain points, players create words from a random assortment of letters in a 5x5 grid. Words can be created from adjacent letters – that is, letters which are horizontal or vertical neighbors of each other as well as diagonals. The letters must connect to each other in the proper sequence to spell the word correctly. This means that the next letter in the word can be above, below, left, or right of the previous letter in the word (excluding any letters previously used to construct the word). 

## Getting Started

```python
git clone git@github.com:shushruthab/boggle.git
cd boggle

# Run virtual environment
python3 -m venv venv
source venv/bin/activate

# Install dependencies
pip3 install -r requirements.txt

# Run server
flask run

# Server runs on http://localhost:5000
```