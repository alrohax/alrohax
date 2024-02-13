<h2 align="center">About Me </h2>

```python
from typing import Tuple, List, Dict

class alrohax:
    pass

class Attributes(alrohax):
    @property
    def contact(self) -> Tuple[str, str, str]:
	discord  = "alroha"
	return discord

    @property
    def life(self) -> Tuple[List[str], int]:
	langs = ['Danish', 'Spanish', 'English']
	age   = 15
		
	return langs, age
	
    @property
    def coding(self) -> Tuple[Dict[str, List[str]], List[str], List[str]]:
	langs = {
	    'expert'      : ['python'],
	    'intermediate': ['c++'],
	    'learning'    : ['java']
	}
	specialities  = ['cyber security', 'game hacking']
	environnement = ['vscode']

	return langs, specialities, environnement
```python
