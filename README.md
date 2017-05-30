# Anki-Youdao
Sync your Youdao worldlist to Anki.

![](https://ws4.sinaimg.cn/large/006tNc79gy1fg3rq9lgomj31io0o8kjl.jpg)
# Require
* Python 2.7
* Python modules
* * flask
* * lxml
* * requests

# Usage
* Move Youdao-wordlist to Anki add-on folder and restart Anki.
* Open up ```serverSide.py``` with your favorite edit and change the proper ```Username ``` and ```Password``` at the very end of this file.
* Open up terminal cd to the serverSide.py folder, than run ```python serverside.py```.
* Navigate to ```Anki```->```Tools```->```Import your youdao-wordlist```.
* Change the ```Server Address``` to ```http://127.0.0.1:5000``` and type the Deck name you want to sync to.
* Press Sync button
* Done~
![](https://ws4.sinaimg.cn/large/006tNc79gy1fg3ru3etdmg30k00cikjr.gif)

# Notice
* The ServerSide.py will gernerate cookie and cached file please do not delete or modify them Unless your want to reinitialize.  
* please don not visit the server address by your browser, this opearation will screw all process up!!! Trust me~~