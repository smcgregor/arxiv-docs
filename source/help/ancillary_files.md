Ancillary files
===============

**Please note that the ancillary
files feature is *not* supported with [PDF submissions](submit_pdf.md) at this
time. They are only supported for submissions with TeX/PDFLaTeX source files.**


arXiv is primarily an [archive and distribution service for research
articles](../about/index.md). There are limited facilities for including ancillary
files with articles. Such ancillary
files might include:

-   Raw data for tables and plots in the article
-   Program code
-   Additional images or movies
-   Workbooks and spreadsheets

arXiv accepts ancillary material only in support of research articles
submitted. Please take note of the following submission tips:
 
- TeX files should not be included in the ancillary file directory. 
- Pointers inside your codebase should not reference this directory (linking may be lost upon announcement). 
- Full text placed in the ancillary directory will not be indexed in searches.
- PDF files with embedded JavaScript will cause your submission to fail (embedded JavaScript is a security risk to arXiv’s systems).
    - Remove or disable JavaScript when building your PDF or generate PDFs using standard tools such as Adobe Distiller.
    - Submit all movies and animated GIFS as separate (non-JavaScript) ancillary files. 


Submission of ancillary files
-----------------------------

Ancillary files are included with an arXiv submission by placing them in
a directory `anc` at the root of your .tar.gz or .zip submission package.
This is done in the "Add Files" step of the submission process.

For example, if
the submission has one TeX file, one image, and C++ program the tar/zip
submission package might be:
```
    /article.tex
    /figure1.pdf
    /anc/my_program.cpp
```
Ancillary files are stored with a particular version of an article and
thus cannot be changed independently from the article. Different
ancillary files may appear with each version.

Display and download
--------------------

The abstract pages for articles that include ancillary files will
include additional links below the usual article download links. See,
for example, [arXiv:0811.2625v2](https://arxiv.org/abs/0811.2625v2). There is also a
separate page that lists all ancillary files with greater detail than
there is room for on the abstract page. See, for example, [ancillary
files for arXiv:0905.2326v1](ancillary_files.md). In both cases there
are links to each file for individual download. Ancillary files are also
included in the complete article source that may be downloaded from the
[other formats](https://arxiv.org/format/0905.2326v1) page.
