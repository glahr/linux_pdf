# linux_pdf

This repo is just to organize some info about pdf handling with Linux, such as merging, compressing, splitting, and other useful functionalities.

# Compressing files: shrinkpdf.sh

Compress bash file is credited to [alfredklomp](http://www.alfredklomp.com/programming/shrinkpdf/). This guys automates ```ghostscript```.

1) Do not forget to make ```chmod +x shrinkpdf.sh``` before using it.
2) Typical usage: ```./shrinkpdf.sh in.pdf > out.pdf``` or ```./shrinkpdf.sh in.pdf out.pdf```
3) For choosing desired output dpi: ```./shrinkpdf.sh in.pdf out.pdf 90``` (72 is the defaultand is way too shrinky).

# Merging files

This uses ```pdfunite``` which is part of ```poppler``` and is probably already installed in your Linux.

Just use: ```pdfunite in-1.pdf in-2.pdf in-n.pdf out.pdf```
