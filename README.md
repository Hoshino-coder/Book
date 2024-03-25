# 作品について
今回作成した製作物は『野菜の収穫を予測した自動判別機』である

![image](https://github.com/Hoshino-coder/Book/assets/154045874/f4768797-0807-43c5-9eff-ff6afbdde5bf)

マイコンはSONY製のSPRESENSEを使用している

この製作物では，野菜の収穫時期を予測するために，SPRESENSEのカメラボードを使用して機械学習を行い予測を行っている．ここで，野菜の収穫を予測した自動判別機の製作から実際に動かすまでの手順を以下に示す．

・必要な部品の準備

・製作物の構成

・プハードの設計

・ソフトウェアの設計

以下ではこれらを詳細に述べる．

# 必要な部品の準備

下記の部品表の通りに各種部品を用意する．

![image](https://github.com/Hoshino-coder/Book/assets/154045874/cb7c5430-51b0-4a4f-9bf9-a88c850782bb)

# 製作物の構成

ここで，製作物の構成について示す．下図より，SPRESENSEを使用しここでは，ネオピクセルを接続する．また，SPRESENSEに付属しているカメラボードを使用してプランターの野菜を撮影するため，LCDキットを接続することにより，野菜の様子を見ることが出来る．（参考：https://github.com/autolab-fujiwaratakayoshi/MIC-LCD_kit_for_SPRESENSE）

![image](https://github.com/Hoshino-coder/Book/assets/154045874/66e36f39-efe9-47d4-903d-999e55a0375f)

![IMG_7354](https://github.com/Hoshino-coder/Book/assets/154045874/f975193f-f003-4774-81bd-c9bf53e06008)

# ハードの設計

ここで，ハードの設計について示す．ここでは，木製の

# ソフトウェアの設計

# リポジトリの構成

・Spresense：SPRESENSE内で使用した処理

・Program：製作物の動作に関するプログラムのリスト
