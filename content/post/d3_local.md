---
title: "Testing D3 projects locally"
date: 2023-03-08T09:28:00+02:00
draft: true
tags: ["D3"]

---

# Setting up a local server
Python is already installed on my laptop.
In a new terminal window:
Navigate to the directory to be served:
`cd 1_Data_Analysis/projects/d3_projects`
Enter:
`python -m SimpleHTTPServer 8888 &`


# Test Quarto

Install Quarto : https://quarto.org/docs/get-started/

Install required libraries in a terminal (in a specific folder linked to python3 that Quarto is using):
`cd Library/Developer/CommandLineTools/usr/bin/python3` (root: cd ../.. from User/linetonthat)
`python3 -m pip install jupyter jupyterlab matplotlib plotly`

Copy an example into a text file with .qmd extension: https://quarto.org/docs/get-started/hello/text-editor.html

In a terminal, navigate to my quarto projects folder and enter:
`quarto render hello.qmd --to html`

A HTML file is created, along with folders hello_files containing mainly libraries and images.

You can only preview it at http://localhost:4673/, by entering:
`quarto preview hello.qmd`
