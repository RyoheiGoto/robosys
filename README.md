# robosys
ロボットシステム学2017 第1課題 デバイスドライバ

#### 内容
**デバイスファイルへ書き込まれた0~9の数字が素数かを判別してLEDを点滅させる
素数の場合LEDをON, それ以外の場合はOFFになる

#### 使用方法
LEDをGPIO25へ接続する

`$ git clone https://github.com/RyoheiGoto/robosys.git`
`$ cd robosys`
`$ make`
`$ ./install.sh`
`$ echo 0 > /dev/primenumled0`

#### 動作動画
