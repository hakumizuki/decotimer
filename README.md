# Alpha  
Decotimer is now alpha stage.  
Throw me issues!  

# Environments
```
Python: >=3.6, <4
```

# Requirements
```
pip install pathlib
```

# Try decotimer with docker
```
$ cd <parent dir of decotimer>
$ docker build -t decotimer .
$ docker run --rm decotimer
```

# decotimer
(TBD)  

English:  
It allows you to calculate run time of each functions. See USAGE.md for (more information)[https://github.com/hakumizuki/decotimer/blob/main/USAGE.md]  

```
timer = Timer()
@timer.use_timer
def do_something():
    ...

do_something() # this prints the results
```

Other functions:  
You can divide process into blocks and name them.  
Coming soon --> File exporting (JSON, CSV)  


Japanese:  
Python3の関数内の処理時間を計算します。  

```
timer = Timer()
@timer.use_timer
def do_something():
    ...
```

として関数を呼ぶだけで計測できます。  

他にも、、、  
Blockで処理を分割したり、処理に名前をつけたりできます。  
今後ファイル化(JSON、CSV)も考えています。  

# Test decotimer
```
$ docker run --rm decotimer python -m unittest
```
Note: It might fail depending on your pc spec.  

# Author
* Taichi Masuyama
* montanha.masu536@gmail.com

I always welcome your ideas!  
Thanks for visiting my repo :)  

# License
"decotimer" is under [MIT license](https://en.wikipedia.org/wiki/MIT_License)  
