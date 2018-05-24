Econometrics Notation
===

Standard notation for econometrics from ([Abadir and Magnus, 2002](http://onlinelibrary.wiley.com/doi/10.1111/1368-423X.t01-1-00074/abstract)). Zip file can currently be downloaded from [here](http://janmagnus.nl/misc/notation.zip)

In order to test if the package is correctly installed run

```
pdflatex cheatsheet.tex
```

# Installations instructions for MAC

## First install

```
mkdir -p ~/Library/texmf/tex/latex/custom/
ln -s ~/Documents/projects/github/econometrics-notation/ee.sty ~/Library/texmf/tex/latex/custom/ee.sty
```

## Updates

```
sudo texhash
sudo mktexlsr
```

# Installations instructions for windows

## First install

```
mkdir -p ~/texmf/tex/latex/custom/
```

In the Start Menu go to the MiKTeX entry and open the settings – if you act as admin respectively “Settings (Admin)”, of course. The “MiKTeX Options” window will open. Open the MiKTeX Console and go to the “Directories” tab in the "Settings" menu. Click on “+” and choose `~/texmf/tex/latex/custom/`. 

```
cp /d/projects/econometrics-notation/ee.sty ~/texmf/tex/latex/custom/ee.sty
```

Now go to the "Tasks" menu and click on "Refresh file name data base"

## Updates

```
cp /d/projects/econometrics-notation/ee.sty ~/texmf/tex/latex/custom/ee.sty
```

Now go to the "Tasks" menu and click on "Refresh file name data base"