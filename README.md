# MarvelNetwork

This repository conatains a script that allows for converting a CSV file to gexf, which can then be exported as SigmaJS network and hosted using GitHub pages.

## Data Source

The data was downloaded from [Kaggle](https://www.kaggle.com/csanhueza/the-marvel-universe-social-network)

## Deployed Network Graph
Click here to get to the deployed [Marvel Network Graph](https://tdenzl.github.io/MarvelNetwork/network/#)

## Medium Article
Make sure to also check out the accompanying [Medium article](https://tim-denzler.medium.com/from-csv-to-github-pages-in-5-steps-publishing-an-interactive-social-network-of-the-marvel-7b8374bf44fb)

## Current Data Scope
* :superhero_man: :superhero_woman: 6,426 Characters
* :books: 224,181 Co-cccurrences in Comics

## Repository Structure
| Folder/Code | Content |
| ------------- | ------------- |
| data | Contains the comic data in csv format, as well as the gexf graph|
| network | Contains the Sigma JS network |
| csv2gexf_conversion.ipynb | Jupyter Notebook used for data converting CSV to gexf |

