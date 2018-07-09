# Katalon-Keywords

Katalonの[Built-in keywords](https://docs.katalon.com/display/KD/Mobile)でやることできない操作をCustom keywordを作ってやることできます。


## Custom Keyword作成


### JavaでCustom Keyword作成
必要なJava LibrariesをダウンロードしてKatalonのExternal Librariesに追加します。
 パス：Project > Settings > External Libraries.
  - Junit (junit-4.12.jar)
  - Java-client (java-client-5.0.3.jar)
  - Selenium (Selenium-java-2.41.0.jar)
  - Java-util (java-util-1.3.1.jar)
  - commons-lang(common-lang3.3.7.jar)

詳しくいステップIssues＃1

ターミナルを開いてKatalonフォルダーのKeywordsフォルダーを開きます。
例えばプロジェクトフォルダーパスはKatalon Studio/myprojectの場合、

$ cd Katalon\ Studio/myproject/Keywords/

Gitレポシトリから全てのファイルをcustomkeywordsフォルダーの中にダウンロードします。

$ git clone https://github.com/monstar-lab/katalon-custom-keyword-ios.git customkeywords
