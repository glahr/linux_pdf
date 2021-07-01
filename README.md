# linux_pdf

This repo is just to organize some info about pdf handling with Linux, such as merging, compressing, splitting, and other useful functionalities.

# shrinkpdf.sh

Compress bash file is credited to [alfredklomp](http://www.alfredklomp.com/programming/shrinkpdf/).

1) Do not forget to make ```chmod +x shrinkpdf.sh``` before using it.
2) Typical usage: ```./shrinkpdf.sh in.pdf > out.pdf``` or ```./shrinkpdf.sh in.pdf out.pdf```
2.1) Or for multiple: ```./shrinkpdf.sh in1.pdf in2.pdf in3.pdf out.pdf```
3) For choosing desired output dpi: ```./shrinkpdf.sh in.pdf out.pdf 90``` (72 is the defaultand is way too shrinky).
