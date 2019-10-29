# Introduction

Data Science is a mixed of 

- Hacking Sills
- Math & Stats
- Subject Expertise
- Detective Skills!

This repo only contains one example but many, many more can be found [here](https://github.com/joelgrus/data-science-from-scratch). This is from Joel Grus's amazing Book, <u>Data Science from Scratch</u>.



![Capture]((https://github.com/katsully/data-crash-course/blob/master/Capture.png)

Data can be complex, enormous, and beyond tedious to parse by hand. This is why we need tools, like Python to help us. Data can be used to determine Twitter trends, pinpoint where epidemics began, and Facebook even used their data to draw out [global migration patterns](https://www.facebook.com/notes/facebook-data-science/coordinated-migration/10151930946453859/).

# Example Dataset

This repo uses a CSV (comma separated values) file from [NYC OpenData](https://opendata.cityofnewyork.us/data/) about all complaints received pertaining to the Department of Buildings. Download the data set as a CSV file [here](https://data.cityofnewyork.us/Housing-Development/DOB-Complaints-Received/eabe-havv). Be sure to save the file inside this repository's folder! Some of these columns contains codes such as Disposition Codes and Complaints Categories and codes are not very helpful, so to help 'decode' this dataset I've included some resources:

- [NYC Complaint Categories](https://www1.nyc.gov/assets/buildings/pdf/complaint_category.pdf) 
- [NYC Disposition Codes](https://www1.nyc.gov/assets/buildings/pdf/bis_complaint_disposition_codes.pdf)

# Getting Started

First, you want Python installed on your computer. (Mac comes with Python already installed) You can download Python [here](https://www.python.org/downloads/release/python-375/). I recommend using the macOS 64-bit installer for Mac users (if Python is not already installed) and the Windows x86-64 executable installer for Windows. (Be sure to include Python in the PATH during installation!)

You'll also need to install Jupyter Notebook. Following the directions from the [official site](https://jupyter.org/install), in terminal (or Command Prompt for Windows) you'll want to type the following commands:

`python -m pip install --upgrade pip`

`python -m pip install jupyter`

We also need to install two Python modules, pandas and matplotlib. To do this we'll type (in the terminal)

`pip install pandas`

`pip install matplotlib`

Finally we'll run `jupyter notebook`. Be sure to run this command from the folder where you downloaded the repo!



Questions? Concerns? Please create an issue in the repo!