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


## Customkeywordsを新しいProjectに追加する方法
 - Katalonを開きます。
 - Katalon Studio > Preferences > Katalon > Gitを開いてEnable Git IntegrationをチェックしApplyとOKをタップします。
 - Menu barにGitアイコン表示しますので　Git > Clone　Projectクリックします。
 - Repository URLを「https://github.com/monstar-lab/katalon-custom-keyword-ios/」入れます。
 - 次の画面Next、Next、Finishクリックします。
 - katalon-custom-keyword-iosと新しいprojectを作成された事確認します。
 - katalon-custom-keyword-ios　Projectを開きKeywordsフォルダー中にGitからCustom　Keywordsをコピーしている事確認
 - Project > SettingsからProjectの名前を変更できます。
