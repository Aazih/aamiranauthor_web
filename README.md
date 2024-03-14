# aamiranauthor_web

## Purpose

The purpose of this project is to create a Material for Mkdocs website, not as a documentation portal, but for my personal website as an author.

The purpose of this readme is to document the steps I went through to install and use Material for Mkdocs as I find it incredibly valuable for my very limited memory to refer back to what I actully did.

While this is a personal reference, perhaps the step by step approach might be of use as a reference for someone else as well.

## Initial Steps

1. Create github repository (in previously existing github account)
2. Install Git for Windows
3. Clone repository via Visual Studios Code and https
4. Start updating readme
5. Create python virtual environment using `py -m venv venv`
6. Activate python virtual enviornment ` .\venv\Scripts\activate` (Windows)
7. Within python virtual environment: Install material-mkdocs `pip install mkdocs-material`
8. Within python virtual environment: Create new mkdocs site `mkdocs new .`
9. Update mkdocs.yml: add material theme `theme:  name: material` (two separate lines)

