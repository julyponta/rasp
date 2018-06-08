# ラズベリーパイ起動用SD作成

## 手順

### windows10での作業
1. sdカードフォーマット
2. noobsをsdカードをコピー

### ラズベリーパイでの作業
3. sdカードをセットして起動
4. wifiと言語選択
5. Rasbianをインストール
   * 約30分程度掛かる
6. リブート
7. フォントインストール
   * sudo apt-get update
   * sudo apt-get upgrade
   * sudo apt-get install fonts-ipafont fonts-ipaexfont
8. 日本語入力インストール
   * sudo apt-get install ibus-mozc
9. リブート
10. 各種設定
   * タイムゾーン Asia,Tokyo
   * キーボード そのまま
   * ロケール そのまま
   * 無線LANの国 JP JAPAN
11. リブート 

