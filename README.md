# Resume

Personal Resume written in LaTeX.

## Installation

1. Install BasicTex from [here](https://www.tug.org/mactex/morepackages.html). It should install into `/usr/local/texlive/2016basic`.

2. Install the `fonts/` for use by latex.

3. There will be several packages missing. If you try to compile and it fails with the warning of `<somefile>.sty` is missing, use the `tlmgr` binary to install those `<somefile>`s:

    ```shell
    cd /usr/local/texlive/2016basic/bin/universal-darwin
    sudo ./tlmgr install textpos
    sudo ./tlmgr install isodate
    sudo ./tlmgr install substr
    sudo ./tlmgr install titlesec
    ```

4. Then, compile your tex file into pdf:

    ```shell
    xelatex keng_resume-openfont.tex
    ```

    It should output a pdf.



