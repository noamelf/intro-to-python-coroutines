Installation:
```bash 
virtualenv . -p /usr/bin/python3  
source bin/activate  
pip install -r requierments.txt 
```

Run notebook:
``` 
bin/ipython notebook
```

Present slides:
``` 
bin/ipython nbconvert intro-to-coroutines.ipynb --to slides --post serve
```
