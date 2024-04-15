# Web Scraping and NLP with Requests, BeautifulSoup, and spaCy

Complete the tasks in the Python Notebook in this repository.
Make sure to add and push the pkl or text file of your scraped html (this is specified in the notebook)

## Rubric

* (Question 1) Article html stored in separate file that is committed and pushed: 1 pt
* (Question 2) Article text is correct: 1 pt
* (Question 3) Correct (or equivalent in the case of multiple tokens with same frequency) tokens printed: 1 pt
* (Question 4) Correct (or equivalent in the case of multiple lemmas with same frequency) lemmas printed: 1 pt
* (Question 5) Correct scores for first sentence printed: 2 pts (1 / function)
* (Question 6) Histogram shown with appropriate labelling: 1 pt
* (Question 7) Histogram shown with appropriate labelling: 1 pt
* (Question 8) Thoughtful answer provided: 1 pt

# web-scraping
This exercise is used to practice web scraping (fetching and extracting information) and processing the content from a web page. 

## How to Install and Run the Project

```shell
cd C:\Users\AanandyaMittal\Documents\
git clone https://github.com/AanandyaMittal/web-scraping
```

## Virtual Environment Instructions for Creation and Activation

On Windows, create a project virtual environment in the .venv folder. 

```shell
py -m venv .venv
.venv\Scripts\Activate
```

## Install Requests

```shell
py -m pip install requests
```

## Freeze Requirements Instructions

```shell
py -m pip install -r requirements.txt
py -m pip freeze > requirements.txt
```


## Git Commands for Adding, Committing, and Pushing

```shell
git add .
git commit -m "insert commit"
git push -u origin main
```

## Install Jupyter and libraries

```shell
py -m pip install jupyterlab numpy pandas matplotlib seaborn
python -m pip install beautifulsoup4
python -m pip install html5lib
python -m pip install requests
python -m pip install spacy
python -m pip install spacytextblob
```
## To html

```shell
!jupyter nbconvert --to html web-scraping.ipynb
```