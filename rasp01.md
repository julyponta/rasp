# ラズベリーパイ起動用SD作成

## 手順

### windows10での作業
* sdカードフォーマット
* noobsをsdカードをコピー

### ラズベリーパイでの作業
* sdカードをセットして起動
* wifiと言語選択
* Rasbianをインストール
   * 約30分程度掛かる
* リブート
* フォントインストール
   * sudo apt-get update
   * sudo apt-get upgrade
   * sudo apt-get install fonts-ipafont fonts-ipaexfont
* 日本語入力インストール
   * sudo apt-get install ibus-mozc
* リブート
* 各種設定
   * タイムゾーン Asia,Tokyo
   * キーボード そのまま
   * ロケール そのまま
   * 無線LANの国 JP JAPAN
* リブート 

