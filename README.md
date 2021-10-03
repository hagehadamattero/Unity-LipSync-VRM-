# Unity-LipSyncWithText-VRM
リップシンクLipSyncをさせるスクリプトは、音声入力のものしか見つからなかったので、テキスト入力のものを作りました。
Unityで、VRMのブレンドシェイプを用いて、入力した文章に合わせて口を動かします。VRMモデルにアタッチし、インスペクターに入力した文字の通りに口を動かします。
VRMモデルにはVRM Blend Shape Ploxyをアタッチしておいてください。
小文字を除くひらがなに対応しています。

＜問題点＞
「しゃ」等は「し」と「や」に分解されてしまいます。
