# ロボットシステム学　課題1  
17C1045 清岡優祐　　

## 実装内容  
入力する数字(1~3)によってLEDの消灯時間が変化します。  
１の場合１秒、２の場合２秒、３の場合３秒。  

## 環境構築  
`git clone https://github.com/YusukeKiyooka/LED.git`  
`cd LED`  
`make`  
`sudo insmod myled.ko`
`sudo chmod 666 /dev/myled0`
