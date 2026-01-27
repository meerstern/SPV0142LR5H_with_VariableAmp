# 可変アンプ内蔵アナログ出力MEMSマイク変換基板 SPV0142LR5H
The Converter board of SPV0142LR5H with Variable Apmlifer

## 概要

  * 最大約50倍の増幅回路[TLV316][0]Syntiant社製[アナログ出力MEMSマイクSPV0142LR5H][1]を搭載した2.54mmピッチ変換基板です。  
  * 可聴音から超音波(100Hz～80kHz)までの幅広い帯域を高感度にセンシングすることが可能です。  
  * 周波数特性が非常にフラットです(20Hz~10kHz±2dB、10kHz~80kHz±10dB)
  * 超音波センサや超音波通信などに使用可能です。  
  * RV1により約1倍～約50倍まで変更することが可能です。  
  * アンプ回路を搭載することでArduinoといったマイコンのアナログ入力に直接接続できます。  
  * マイク穴は基板裏面の丸印部分です。  
  * 電源電圧1.8V~3.6V
  * SPU0410LR5Hの後継品でフットプリントを除いて周波数特性や電気特性がほぼ同じです。


## 超音波マイク比較
 用途に応じて様々な製品をラインアップしています  
| 製品名 | 出力 | アンプ搭載有無 | 用途 | 
|:-----------|:------------|:------------|:------------|
| [アナログ出力マイク][A] | アナログ | 無 | 任意のアンプ回路を使用したい場合 | 
| [可変アンプ内蔵アナログ出力マイク(本製品)][B] | アナログ | 有(可変1~50倍) | 増幅率の調整が必要な場合 |	
| [アンプ内蔵アナログ出力マイク][C] |	アナログ | 有(固定50倍) | 一定した増幅が必要な場合	| 
| [デジタル出力マイク][D] |	デジタルPDM | 不要 | フルデジタルで実装する場合やワイドレンジが必要な場合 | 

## 販売サイト
  * [スイッチサイエンス][2]

<img src="img/img1.jpeg" width="360">

<img src="img/img2.jpeg" width="360">

## 告知
SPU0410LR5Hの生産完了に伴い、後継品のSPV0142LR5Hに移行しました。

License - MIT

[1]: https://static1.squarespace.com/static/6488b0b8150a045d2d112999/t/67caf41d815fb04909623d2d/1741354016529/SPV0142LR5H-1-datasheet.pdf
[0]: http://www.tij.co.jp/product/jp/TLV316
[2]: https://www.switch-science.com/products/6583


[A]: https://github.com/meerstern/SPV0142LR5H
[B]: https://github.com/meerstern/SPV0142LR5H_with_VariableAmp
[C]: https://github.com/meerstern/SPV0142LR5H_with_Amp
[D]: https://github.com/meerstern/SPH0641LUAmp
