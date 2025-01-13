# Latex template for PhD thesis at IP Paris (Institut Polytechnique de Paris)

Please check on ADUM to see whether this template still matches their recommendations (especially first page and last page) before using it for yourself. This is not an official template for IP Paris thesis. The template is modified from the Paris-Saclay template of bmazoyer and riverarodrigoa. 

## How to use this template
The main file is [thesis.tex](thesis.tex).

To add your name, the title of your thesis, the jury members, the school logo, you should modify:

* [layout/firstpage](layout/firstpage.tex)
* [layout/lastpage](layout/lastpage.tex) 
* [thesis.tex](thesis.tex)

To add acknowledgements or a dedication, you should modify:

* [layout/acknowledgements](layout/acknowledgements.tex)
* [layout/dedication](layout/dedication.tex)

The content of the thesis chapters is in:

* [1](1.tex)
* [2](2.tex)
...

The content of the appendices is in:

* [appendices/1](appendices/1.tex)
* [appendices/2](appendices/2.tex)
...

In case you add or remove a chapter file or an appendix file, don't forget to update 
the corresponding variable (`\NumOfChapters` or `\NumOfAppendices`) in [thesis.tex](thesis.tex).


