# qiita-AtCoderTemplate
本テンプレートはAtCoderの回答を簡単に実行するものです。  
よく使う関数をmain.pyに記載しておくととても便利です。  
ぜひforkしてカスタマイズしてください！

# 必要環境
実行環境：Windows  
AnacondaやPythonがインストールされていること。

# 環境設定方法 (Anacondaの場合)  
Batファイル"check.bat"を実行すると、コマンドプロンプト上でpythonを実行します。  
コマンドプロンプトからpythonを実行できるように環境変数PATHを設定する必要があります。  
(特に、Anacondaをインストールしている場合)

# 使用方法
1. templateフォルダをダウンロードする。
2. templateフォルダをコピーする。  
もしあなたがAtoCoderのABC110のA問題を解く場合、フォルダ名称を"ABC110A"とすることをお勧めします。

3. 入力ファイルを設定する。  
AtCoderの問題には、サンプルの入力例が1件～3件あります。  
フォルダの中の"in1.txt"～"in3.txt"に入力例をコピーしましょう。

4. 解法をmain.pyのmain()関数に書きましょう。  
main.pyのmain()にあなたの解法を記載します。

5. 結果を確認しましょう。  
同梱のcheck.batをダブルクリックで実行してください。  
check.batは"in*.txt"を自動で検出して、main.pyを実行します。  
![結果](https://github.com/marimoon/qiita-AtCoderTemplate/blob/main/img_readme/result.JPG)  
実行時間も表示されますので、問題に記載されている実行時間に間に合うか分かります。  

6. 解法の提出  
main.pyの中身をAtCoderのソースコード欄に張りつけて、「提出」ボタンを押すだけです！
