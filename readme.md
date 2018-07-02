# ScienceBase API Demo 

Quick reference for working with sciencebase.gov using python. Please install the sciencebase python package from the recommended source (https://code.chs.usgs.gov/sciencebase/pysb.git)

### Quick Start

```python
import pysb

sb = pysb.SbSession()

# get item
my_item = sb.getSbItem('55c27fe1e4b033ef5210686e')

# login -- provide password
sb.loginc('username@usgs.gov')
```

### Requirements

* Python 3.6+
* PySB [pysb](https://code.chs.usgs.gov/sciencebase/pysb.git)
