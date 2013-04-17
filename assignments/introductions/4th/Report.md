Assignment Report for 1.4
------

以下に、課題の回答を記入してください。

Android の基礎知識
======

4. `adb`コマンドを使って、下記の項目を実行してください（課題のファイルに、実行したコマンドを記録しておいてください）。

端末のSD カード領域に、ローカルにあるファイルを転送する

adb push ~/Documents/images.jpeg /sdcard/

端末のSD カード領域から、ローカルにファイルを転送する

adb pull /sdcard/DCIM/Camera/IMG_20130408_115107.jpg ~/Downloads

課題用サンプルプロジェクトの apk ファイルをコマンド経由で端末にインストールする

adb install AndroidTraining/practice/introductions/3rd/firstApp/firstApp.apk