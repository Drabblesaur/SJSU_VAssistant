# SJSU_VAssistant
San Jose State CMPE 259 Final Project.  University Course Advisor &amp; Degree Audit Virtual Assistant

This folder contains all the code needed to run the final project for CMPE 259. Below are the files and what they do:

## Main Files: Contains all the Architecture, Agent, Tools, and Helper Functions
- Final Notebook Large Model.ipynb
- Final Notebook Small Model.ipynb

## Vector Store Setup Files: Processes all scraped information and builds vector stores. Stores are then saved locally into CMPE259FinalContent
- 259FinalProjectVCLocal.ipynb

## Web Scraper Files: Contains code needed to scrape certain parts of the SJSU website. Note that some files that live in the Documents folder were not scraped but were downloaded via SJSU.
- GAPEScraper.ipynb
- GradMajorReqScraper.ipynb
- RegistrarScraper.ipynb

## CMPE259 FinalContent & Documents
This folder contains all the necessary files needed to run the project. Any notebooks that produce content have their outputs are sent here. Documents is a folder that contains some files that were downloaded manually in the SJSU site.

## Notes
259FinalProjectVCLocal.ipynb takes a bit of time to run. It's not necessary to run this notebook ( I’ve provided you with the local vector store data needed to load the vector stores)
At a minimum, it's recommended that you run the final project code using a T4 GPU. For the Large Model, using a strong GPU will get you faster times.
A PDF of the outputs is provided for the 2 final notebooks.
