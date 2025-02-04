## ファームウェアのアップデート
バグの修正や機能の追加等でファームウェアがアップデートされることがあります。

まず現在基板に書き込まれているファームウェアのバージョンを確認し、もしGithubで公開されているバージョンよりも古い場合はアップデートをお願いします。

## 書き込まれているファームウェアバージョンの確認方法
Ethernet経由でOSCから確認する方法と、USB経由でシリアルモニタから確認する方法があります。
### OSCから確認する
`/getVersion` メッセージで現在のファームウェアバージョンを確認できます。詳しくはコマンドリファレンスの[`/getVersion`](https://ponoor.com/docs/step-series/osc-command-reference/system-settings/#getversion)を確認してください。

### USBから確認する
本デバイスとPCをUSBで接続し、シリアルモニタから`s`を送信すると得られるステータスから現在のファームウェアバージョンを確認できます。
詳しくは[USBシリアルからの診断](https://ponoor.com/docs/step-series/technical-information/diagnosis/)の「[Firmware](https://ponoor.com/docs/step-series/technical-information/diagnosis/#firmware)」を確認してください。

## 現在の最新バージョン番号の確認方法
各機種のGithubリポジトリの「Releases」から確認してください。

| 機種 | リポジトリ |
| --- | ---|
| STEP400 | https://github.com/ponoor/STEP400/releases |
| STEP800 | https://github.com/ponoor/STEP800/releases |


## ファームウェアをアップデートする
基板に書き込まれているファームウェアが古くなっていた場合はアップデートをお願いします。アップデートはArduino IDEからArduinoスケッチをコンパイル＆書き込みすることによって行います。詳しくは「[Arduinoスケッチのコンパイル](https://ponoor.com/docs/step-series/technical-information/compile-the-arduino-sketch/)」を参照してください。


