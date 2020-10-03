# Rocket Vocab
The simple app for learning vocabulary on terminal

## Install 
1. Via pip3
```
pip3 install rocket-vocab
```

2. Manual
```
git@github.com:huongnhdh/rocket-vocab.git
cd rocket-vocab
python3 setup.py install
```

3. Some when install problems

3.1) If has error is  `WARNING: The script rocket is installed in '/home/${USERNAME}/.local/bin' which is not on PATH.`


```
#Please append  $HOME/.local/bin to $PATH var by 
echo 'export $PATH=$HOME/.local/bin:$PATH' >> ~/profile

#then 
exec $SHELL
```

## How to use 
```bash
user-> rocket 
start learing....
Many the words you want to train? > 2
------------------------
Are you remember it? remote
------------------------
y|n|uhm|c|  > y

Great!




------------------------
Are you remember it? screen
------------------------
y|n|uhm|c|  > n

Oh no!
https://www.google.com/search?q=how+to+pronounce+screen
https://www.google.com/search?q=screen+l%C3%A0+g%C3%AC



Ya You're finish challenge!
user-> 
```

## TODO://

0. Intergation with FireBase
1.  ~~Make package on Pypi~~
2. Classify by know-point
3. Random by classify
4. More color with `TrueColor`
