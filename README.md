# CARVS
## 注意事項
少なくともv0.0.0.6までは一部の攻撃に弱いため、<br>
Bitlockerを用いた追加の保護を推奨いたします。
## 概要
WindowsユーザーのパスワードをOTPにします。<br>
万が一不具合等でログインできなくなると困るので<br>
パスワードをリセットできるようにしておくことをお勧めしております。
## 注意事項
※利用にはスマホとGoogle Authenticatorが必要です<br>
※Windows Defender以外のセキュリティソフトをご使用の際は、<br>`c:\passchange.exe`を念のため検知除外リストに追加することをお勧めいたします

## セットアップ
起動できない場合、Visual StudioのCランタイムがないから起動できない可能性が高いです。<br>
なので以下のVisual Studio C Runtimeをインストールするとご利用可能です。<br>
以下ののサイトからできるだけ日付が新しいものをダウンロードし、<br>
そのZIPファイルに入っている`install_all.bat`を管理者権限で実行すると自動でセットアップしてくれます。<br>
[必要なランタイムのダウンロードはこちら](https://www.techpowerup.com/download/visual-c-redistributable-runtime-package-all-in-one/)

## お知らせ
 - 使い方や説明動画は近日中に投稿予定です。
 - ソースコードの一部も近日中に公開します。
 - セキュリティ関連の強化、および解析対策の強化等を行っております。
