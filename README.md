# リポジトリの概要
千葉工業大学未来ロボティクス学科2年後期ロボットシステム学の課題2の提出内容となっております。

## 改造内容
今回は授業の内容そのままでの状態での提出となっています。
count.pyで実行からの秒数のカウントを行い、twice.pyでそれを取得し2倍にした数を出力します。

## 動作環境
以下の環境で動作確認を行っています。
* Raspberry Pi 4 ModelB
* OS:Ubuntu 20.04.1 LTS

## インストール方法
`$ mkdir -p catkin_ws/src`  
`$ cd ~/catkin_ws/src`  
`$ catkin_init_workspace `  
`$ cd ~/catkin_ws`  
`$ catkin_make`  
`$ source ~/.bashrc`  
`$ cd ~/catkin_ws/src`  
`$ git clone https://github.com/wadordi/kadai2.git`  
`$ cd ~/kadai2/scripts`  
`$ chmod +x count.py` `$ chmod +x twice.py`  
`$ cd ~/catkin_ws` `$ catkin_make`
## 使用方法
`$ roscore`を行いrosを起動。   
`$ rosrun kadai1 count.py`  
`$ rosrun kadai1 twice.py`  
`$ rostopic echo /count_up`  
`$ rostopic echo /twice` 

## 制作者
Ryuichi Ueda & Tomoki Terasawa

## ライセンス
"kadi2" is under [GPL](http://www.gnu.org/licenses/gpl-3.0.html)
