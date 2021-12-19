# robosys_device_drivers

ロボットシステム学で作成するデバイスドライバーのサンプルです。雑です。

## ラズパイやカーネルのバージョン対応

サンプルなので、自身で変更お願いします。

* Raspberry Pi 3B
    * `myled.c`42行目のGPIOアドレスを「`0xfe200000`」から「`0x3f200000`」に変更
* 新しいカーネル（バージョン: ???以降）
    * `myled.c`42行目の`ioremap_nocache`を`ioremap`に変更


## ライセンス

GPL 3.0
