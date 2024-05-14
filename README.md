# Resume
Built on top of https://www.latextemplates.com/template/developer-cv

## Steps to reproduce env

1. get the latest install script from ctan `wget https://mirror.ctan.org/systems/texlive/tlnet/install-tl-unx.tar.gz`
2. extract `zcat < install-tl-unx.tar.gz | tar xf -`
3. `cd install-tl-* && sudo perl install-tl --profile=../texlive.profile`, the texlive profile here is my texprofile that is installed in my system
4. add tex path to system path
5. update tlmgr - `tlmgr update --self`
6. ```tlmgr install `cat packages.txt````
7. now you have all the necessary pacakges, compile. `pdflatex main.tex`

### References
1. https://www.tug.org/texlive/quickinstall.html
2. https://www.tug.org/texlive/doc/install-tl.html#PROFILES
3. https://www.tug.org/texlive/quickinstall.html#running
4. https://tex.stackexchange.com/questions/528069/tlmgr-install-from-a-requirement-file
5. https://tug.org/texlive/tlmgr.html