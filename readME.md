**Purpose** 

A step-by-step guide on how to read data from Google Sheets using Python. This document is written using Quarto, an open-source publishing tool that enables developers to effortlessly publish their projects with plain text markdown and render them to HTML

**Set up**  

1. Download Quarto at https://quarto.org/docs/get-started/  
2. `pip install -r requirements` to install necessary packages in your virtual environment  
3. Render integrate-python-google-sheet.qmd: Run the following command to render the .qmd file to an HTML file:

       quarto render integrate-python-google-sheet.qmd

   This will generate an HTML file in the same directory.


**Pending**  
Publish to my Github page

**Repository Structure**
```
├── README.md          
│
├── requirements.txt    <- packages to connect and read Google Sheets
|
├── pics                <- demo pics for the document
|
│── integrate-python-google-sheet.qmd                <- instruction how to connect Python with Google sheet in Quarto
|
│── .gitignore         
```
