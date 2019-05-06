# LaTeX template for North East Indian Linguistics

This repo houses the LaTeX template for the papers submitted to the North East Indian Linguistics, the publication of work presented at the North East Indian Linguistics Society conference.

For more information on NEILS, [see sealang.net/neils](http://sealang.net/neils/)

## Using this template

There are two ways to acquire the template files for your submission: downloading the files as a zip archive or cloning the repository. Once downloaded, you can edit `index.tex` with the content of your paper. Scroll down for information on editing.

### Downloading a zip file

The easiest way to download the template is as a zip file. You can download the files by [clicking here](https://github.com/keyilan/neils/archive/master.zip).

### Cloning the repo

To clone to your local system, you must first have `git` installed. If you are already familiar with `git`, simply clone the repo with `git clone https://github.com/keyilan/neils.git` and edit the files from there. Note that you will not be pushing any changes to the master branch.

## Editing

It is important that you do not edit any of the files included in the template except `index.tex`, which holds the contents of your paper, and `references.bib` which contains all previously published works which your paper references.

### Editing references

For a guide on how to write citations in `references.bib`, see [this helpful guide](https://www.economics.utoronto.ca/osborne/latex/BIBTEX.HTM).

## Formatting

#### Glossing

Glossing is handled with `linguex` and `cgloss`.

````latex
\exg.  kaʔ ko nɤ tə-no ʃɯu\\
       down towards {\textsc{prep}} {\textsc{caus}}-extend.horiz {\textsc{imp}} \\~\\
       `point [something] downwards' \label{exg}
````

#### Trees

When possible, use `tikz` for trees.

````latex
\begin{figure}[htpb!]
  \centering
    \begin{tikzpicture}
    \Tree
      [.NP
        [.Det a ]
        [.N'
          [.N tree ]
        ]
      ]
    \end{tikzpicture}
  \caption{This is a figure made with \texttt{tikz}}
  \label{firsttree}
\end{figure}
````

## Questions / Help

For any questions regarding formatting or problems that you may be facing with LaTeX in relation to this template, please get in touch with us. Send a message to Kellen at xxx@xxx.xxx with a description of your problem so that we can help you with a solution.
