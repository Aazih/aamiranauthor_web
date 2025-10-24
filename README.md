# aamiranauthor_web

[![Built with Material for MkDocs](https://img.shields.io/badge/Material_for_MkDocs-526CFE?style=for-the-badge&logo=MaterialForMkDocs&logoColor=white)](https://squidfunk.github.io/mkdocs-material/)

## Purpose

The purpose of this project is to create a Material for Mkdocs website, not as a documentation portal, but for my personal website as an author.

The purpose of this readme is to document the steps I went through to install and use Material for Mkdocs as I find it incredibly valuable for my very limited memory to refer back to what I actually did step by step and decision by decision.

While this is a personal reference, perhaps the step by step approach might be of use as a reference for someone else as well.

## Initial Steps

1. Create github repository (in previously existing github account)
2. Install Git for Windows
3. Clone repository via Visual Studio Code and https
4. Start updating readme
5. Create python virtual environment using `py -m venv venv`
6. Activate python virtual environment `.\venv\Scripts\activate` (Windows)
7. Within python virtual environment: Install material-mkdocs `pip install mkdocs-material`
8. Within python virtual environment: Create new mkdocs site `mkdocs new .`
9. Update mkdocs.yml: add material theme `theme:  name: material` (two separate lines)

## Social Card Steps

1. Install [Msys2](https://www.msys2.org/)
2. Within Msys2 run `pacman -S mingw-w64-x86_64-gtk4`
3. Add to Windows PATH `C:\msys64\mingw64\bin\`
4. Within python virtual environment `pip install "mkdocs-material[imaging]"`

## Ongoing

- From within python virtual environment Run mkdocs webserver locally to view site as is `mkdocs serve`
- From within python virtual environment build site to move to private webspace `mkdocs build`

### Source Control (VsCode Git extension connected to github repo)

1. Create a new branch by hitting branch button in bottom left bar
2. Choose Create a new branch option from top bar, name branch, hit confirm
3. On Source Control Tab: Stage file via + option either next to a file or the top level Changes folder
4. On Source Control Tab: Type Commit Message and hit Commit button
5. On Source Control Tab: Hit Sync Changes (Publish Branch?) button to 'push' to Github

### Source Control (Github)

1. Create pull request between new branch and main
2. Merge pull request
3. Confirm merge
4. Delete branch

## Upload

1. Zip contents of Material for Mkdocs generated site directory
2. Login to cPanel and go to file manager
3. Upload zipped file into aamiranauthor root and extract

## Tools Used

| Tool | Comment |
| --- | --- |
| GitHub | Source Control |
| Visual Studio Code | Code Editor & related tools |
| Python | Language for static site generator |
| Mkdocs | Static site generator using Markdown |
| Material for Mkdocs | Extensive theme for Mkdocs |
| markdownlint VS Code extension | Linter for Markdown |
| Spell Right VS Code extension | Spellchecker |
| Cyberduck | FTP client |
| ASUS laptop | Hardware |
| Windows 11 | OS |

## Credits

Starry effect from: [Ibrahim AbdulHameed](https://codepen.io/Ibrahim-Abdulhameed/pen/oNJMEGV) and [sarazond](https://codepen.io/sarazond/pen/LYGbwj)

## TODO

Future plan: Local linktree
