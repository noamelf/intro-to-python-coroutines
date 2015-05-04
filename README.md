To present slides run:
```bash 
virtualenv . -p /usr/bin/python3  
source bin/activate  
pip install -r requierments.txt 
bin/ipython nbconvert intro-to-coroutines.ipynb --to slides --post serve
```
