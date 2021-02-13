# Country
#### Package published at: [PyPI](https://pypi.org/project/country/)

Python module for country codes with ISO codes.

#### Install:
```bash
pip install country
```

#### Use:
Create a python script, for example **`example.py`**:
```python
from country import country

print('Country code: {}'.format(country.see(country_name='India', option=0)))
print('ISO code: {}'.format(country.see(country_name='India', option=1)))
```
Save and run:
```bash
❯❯❯ py example.py
Country code: +91
ISO code: IN
```

---
#### Author: [Harshil Darji](https://github.com/harshildarji)
