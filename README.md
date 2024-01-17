
# LaTeX Bullet Journal

![latexnb png](https://github.com/rosehaze/LaTeX-Notebook/assets/71717036/f293f224-3e2f-418a-a4da-36511b9a4f07)

Have you ever been sitting in a mathematics lecture and thought to yourself "I wish this LaTeX document looked more like a physical notebook?" No? Just me? Ok.


## Screenshots

🚧 Under Construction 🚧

## Table of Contents
 - [Installation](https://github.com/rosehaze/Bullet-Journal#installation)
 - [Screenshots](https://github.com/rosehaze/Bullet-Journal#configuration)
 - [Why](https://github.com/rosehaze/Bullet-Journal#why)

## Installation

### Download the Notebook

```
$ git clone [https://github.com/rosehaze/LaTeX-Notebook.git]
```

### LaTeX Version
This code is large, and as such, runs most effectively with a full installation of TeX suite and complied with latexmk. As the graphics are complex, compilation time varies.

### Configuration
To use this notebook effectively, it is imparative that the links are configured correctly in the main .tex document.

```latex
% Sections

\import{Sections}{Test_Section_1.tex}

\import{Sections}{Test_Section_2.tex}

\import{Sections}{Test_Section_3.tex}
```

### Error Messages
When compiled, this code will often give the error:

```latex
Underfull \hbox (badness 10000) detected
```
This is due to using \hfill as a way to space paragraphs.


## Why?
When I was initially introduced to LaTeX, I wanted to find a way to personalize my notebooks in the form of a bullet journal.

According to [The LaTeX Project](https://www.latex-project.org/about/):

"LaTeX is not a word processor! Instead, LaTeX encourages authors not to worry too much about the appearance of their documents but to concentrate on getting the right content"

With this in mind, creating a notebook that is heavily stylized to look like a notebook with LaTeX would appear to be in direct conflict with the goal of the language. However, as a computer science enthusiast, LaTeX seemed like the perfect oppertunity to design a notebook that I could love, while also having the ability to create beautiful mathematics equations natively in my document.

It was after reading [this article](https://tex.stackexchange.com/questions/188164/how-to-use-latex-to-print-a-document-to-look-like-a-lined-notebook), and [this post](https://castel.dev/post/lecture-notes-1/) that I decided to make my own. This project is so much fun and I hope you enjoy this template as much as I do. Feel free to customize this template to your heart's content and show me your work!
