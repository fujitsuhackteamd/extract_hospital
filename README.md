# extract_hospital
病院取り出しpythonコード

## 1. 実行について  
conduct.py をコンソール上で動かすことで実行できます．実行後の病院データは，'maindata/nd_hospitaldata.csv' で出力されます．  
また，nd_hospitaldata.csvの形式は，秋元さんが作ってくださったファイルの形式と同様となっています．  
  - 実行形式
  ~~~
  python conduct.py 引数  
  ~~~

## 2. 引数について  
引数は以下の6つあります．  
### 引数リスト
#### 1. path (deault: maindata/hospitaldata.csv)  
実行に必要な，全病院データが格納されているhosipitaldata.csvのパスです (ファイル形式は，秋元さんが作ってくださった形式と同様）．  
#### 2. address_x (default: 0)  
患者の現在位置(経度)です．  
#### 3. address_y (default: 0)  
患者の現在位置(緯度)です．  
#### 4. choice_expert (default: 内科)  
患者が希望する科です．入力は，[内科, 外科, 耳鼻科, 眼科]のうち何れかにしてください．  
#### 5. online_or_visit (default: 来院)  
オンラインか，来院かの情報です．入力は，[来院, オンライン]のうち何れかにしてください．  
#### 6. choice_or_priority (default: 混雑度)  
患者が希望する選好条件です．入力は，[距離, 混雑度]のうち何れかにしてください．
