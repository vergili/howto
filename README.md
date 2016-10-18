
## Selenium==2.47.1  and Firefox 45.0  

### Ubuntu 14.04  Uninstall and Install Firefox

```
sudo apt-get purge firefox

# update version  whatever you want
wget sourceforge.net/projects/ubuntuzilla/files/mozilla/apt/pool/main/f/firefox-mozilla-build/firefox-mozilla-build_45.0-0ubuntu1_amd64.deb


sudo dpkg -i firefox-mozilla-build_45.0-0ubuntu1_amd64.deb


```


### Selenium 
```
sudo pip install selenium=2.47.1
```

### Test 
Below code have to  work on python interpreter

```
from pyvirtualdisplay import Display
from selenium import webdriver
display = Display(visible=0, size=(1024, 768))
display.start()
browser = webdriver.Firefox()
```



