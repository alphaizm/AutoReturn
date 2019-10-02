# AutoReturn
RLogin向けスクリプト

# 目的
以下のような用途で使用するスクリプト

1. あるシステムからコマンドを受信  
　→フォーマットの内容を表示
2. 一定時間待機
3. システムに対してコマンド返信

# 受信フォーマット

1. B　･･･ ASCII
2. R　･･･ ASCII
3. E　･･･ ASCII
4. C　･･･ ASCII
5. V　･･･ ASCII
6. ,　･･･ ASCII
7. RSSI　･･･ binary
8. Role　･･･ binary
9. Method　･･･ binary
10. Length　･･･ binary
11. Data　･･･ 1～20byte

# 送信フォーマット

1. B　･･･ ASCII
2. S　･･･ ASCII
3. E　･･･ ASCII
4. N　･･･ ASCII
5. D　･･･ ASCII
6. ,　･･･ ASCII
7. Role　･･･ binary
8. Method　･･･ binary
9. Length　･･･ binary
10. Data　･･･ 1～20byte
