Assignment Report for 1.3
------

以下に、課題の回答を記入してください。

署名済みアプリの作成
======

3. 作成した apk ファイルの中にあるファイル・ディレクトリを列挙してください。

├── AndroidManifest.xml

├── META-INF

│   ├── CERT.DSA

│   ├── CERT.SF

│   └── MANIFEST.MF

├── classes.dex

├── res

│   ├── drawable-hdpi

│   │   └── ic_launcher.png

│   ├── drawable-mdpi

│   │   └── ic_launcher.png

│   ├── drawable-xhdpi

│   │   └── ic_launcher.png

│   ├── drawable-xxhdpi

│   │   └── ic_launcher.png

│   ├── layout

│   │   └── activity_main.xml

│   └── menu

│       └── main.xml

└── resources.arsc


4. 上記で列挙したファイル・ディレクトリについて、どのような役割を持っているか説明してください。

* AndroidManifest.xml: Androidのマニフェストファイル。アプリケーションの名称やバージョン、使用するアクセス権限などが書かれているXML形式のファイル

* resources.arsc: リソースのうち、各国語対応のための文字列リソースなど、個別ファイルにする必要のないものがxml形式で格納されている。

* classes.dex: dexファイル形式のプログラム（Dalvik仮想マシン用の中間コードである）

* META-INFディレクトリ:  マニフェストファイル。jarファイルから継承したものでファイルの説明が記述されている。

* CERT.DSA: アプリケーションの証明書

* CERT.SF: 各種リソースの保存場所とそのSHA-1ダイジェストの一覧

* MANIFEST.MF: マニフェストファイル。jarファイルから継承したものでファイルの説明が記述されている。

* resディレクトリ: 各種リソースを格納するディレクトリ（アプリが使う画像ファイルや音声ファイルなど）

* drawable-hdpi ,drawable-mdpi, drawable-xhdpi, drawable-xxhdpiディレクトリ:

　　端末の解像度ごとにディレクトリが用意されており、端末の解像度によって、それぞれディレクトリ内の画像ファイルが読まれる

* ic_launcher.png

　　ランチャーアイコン。端末の解像度ごとに用意されている。
