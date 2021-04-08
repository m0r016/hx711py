# HX711 for Raspbery Pi(Ubuntu 20.04LTS)

インストール方法
------------
1. 前提環境のインストール
```
sudo apt install python-is-python3 git gcc python3-dev
```

2. このリポジトリをクローンする
```
git clone https://github.com/m0r016/hx711py
```

3. setup.pyをインストールする。 
```
cd hx711py/
sudo python setup.py install
```

4. 配線し、example.pyを走らせる
配線の位置は↓

|線の色|ラズパイ側|
|---:|---:|
|VDD|2(5v)|
|DAT|29(GPIO5)|
|CLK|31(GPIO6)|
|GND|6(GND)|
|INNB|none|
|INPB|none|

正しく配置できたら
```
sudo python example.py
```
をする。
