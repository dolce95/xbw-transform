# XBWT

This package allows to compute the xbwt transform. This package allows to compute the xbwt transform. The following link refers to the article in which it was defined: https://www.semanticscholar.org/paper/Compressing-and-indexing-labeled-trees%2C-with-Ferragina-Luccio/8c4f49913e8db00dc09c31af480bf4dc37a853d9.

## Installation

```bash
pip install xbwt
```

## Usage from Python3 as a module
It is possible to use `xbwt` directly in a python script by import it.

```python
import xbwt

xbwt_obj = xbwt.readAndImportTree()
xbwt = xbwt_obj.computeXBWT()
xbwt_obj.printXBWT(xbwt)
```

