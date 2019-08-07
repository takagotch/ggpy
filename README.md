### ggpy
---
https://github.com/yhat/ggpy

```py
ggplot(diamonds, aes(x='price', color='clarity')) + \
  geom_density() + \
  scale_color_brewer(type='div', palette=7) \
  facet_wrap('cut')
  
// tests/test_geom_errorbar.py
from ggplot import *

print ggplot(mpg, aes(x='class', y='hwy')) + geom_errorbar()
```

```sh
pip install -U ggplot
conda install -c conda-forge ggplot
pip install git+https://github.com/yhat/ggplot.git
```

```
```


