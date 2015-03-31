# kohl2015latex
Latex version of Current Opinion article written by Kohl, Huoviala and Jefferis.

## compile
You should be able to compile by running `make` in the source directory.  
This is known to work with [MacTex2014](https://tug.org/mactex/).

## fonts
The default font is set to Minion Pro, which may not be available. In that case, comment out as follows

```tex
\setmainfont[Mapping=tex-text]{Minion Pro}
```

to

```tex
%\setmainfont[Mapping=tex-text]{Minion Pro}
```