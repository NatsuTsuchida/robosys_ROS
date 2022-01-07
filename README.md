# robosys_ROS
ロボットシステム学課題２で作成したもの

## 動作環境

・Rasberry Pi4 Model　B

・OS:ubuntu 20.04 server

## 使用したもの

・Rasberry Pi4 Model　B

## 使用方法

・インストール

```sh
$　cd ~/catkin_ws/src
$　git clone git@github.com:NatsuTsuchida/robosys_ROS.git
$  cd ~/catkin_ws
$  catkin_make
```

・roscoreを起動する

```sh
$ roscore &
```

・実行(count)
```sh
$ rosrun mypkg count.py
```

・実行(twice)
```sh
$ rosrun mypkg twice.py
```
## 実行結果





