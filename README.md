# 概要
Multiwiiは任天堂(株)が発売したWiiのヌンチャクコントローラに内蔵されたセンサと、
Arduinoを組み合わせたものが最初のオープンソースなファームウェアです。
Multiwiiに関する詳しい説明は
http://www.multiwii.com/
を参照してください。
# フォルダの説明
```
.
├── I2C_GPS_NAV_v2_2：u-bloxのGPSとi2cで通信するためのファームウェアのソースコード
└── MultiWii_2_3
    ├── MultiWii：MultiWiiのプロジェクトファイルとソースコード
    └── MultiWiiConf：MultiWii起動時のPC上のGUIでボード設定やIMUの情報が取得できるソフトウェア
```