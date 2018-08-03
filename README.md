# Finding_Themes_in_Indonesian_Twitter_with_LDA
Using Latent Dirichlet Allocation to Organize Tweets From Indonesia's 2014 Election

## Getting Started
### Prerequisites
This notebook requires the following packages to be installed:
```
* pandas
* matplotlib
* csv
* re
* gensim
```
The notebook also needs the Indonesian stemmer *[Sastrawi](https://github.com/sastrawi/sastrawi)* installed, which can be done with the following code in your terminal:
```
$ pip install Sastrawi
```
To create the environment, type the following:
```
$ conda create --name py35 python=3.5 pandas matplotlib csv re gensim Sastrawi
```
You can then activate the environment and launch the Jupyter Notebook.
### Data
* [Twitter corpus](https://github.com/aliakbars/bilp) - *courtesy of [Ali Akbar S.](https://github.com/aliakbars)*
* [List of Indonesian stopwords](https://www.kaggle.com/oswinrh/indonesian-stoplist)  - *courtesy of [Kaggle](https://www.kaggle.com)*
* [Sastrawi stemming tool](https://github.com/sastrawi/sastrawi)
### License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
