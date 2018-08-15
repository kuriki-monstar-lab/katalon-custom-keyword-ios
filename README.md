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

------

We can define [custom keywords](https://www.katalon.com/resources-center/tutorials/create-custom-keyword/) to extend the capability of Katalon Studio. Once created, custom keywords can be used in test cases just like other built-in keywords. [Built-in keywords](https://docs.katalon.com/display/KD/Mobile)



### Create Custom Keywords using Java
Download below Java Libraries and add to Katalon [External Libraries](https://docs.katalon.com/display/KD/External+Libraries)
Navigate： Project > Settings > External Libraries.
  - Junit (junit-4.12.jar)
  - Java-client (java-client-5.0.3.jar)
  - Selenium (Selenium-java-2.41.0.jar)
  - Java-util (java-util-1.3.1.jar)
  - commons-lang(common-lang3.3.7.jar)

See Issues＃1 for detailed steps.


## How to use Customkeywords in this project in your new project
 - Open Katalon.
 - Navigate to Katalon Studio > Preferences > Katalon > Git. Check Enable Git Integration and click Apply and OK.
 - Git icon will appear in Menu bar. Navigate　Git > Clone　Project
 - Insert Repository URL「https://github.com/monstar-lab/katalon-custom-keyword-ios/」
 - Keep all the other screen as default and finish.
 - A new project will be created as katalon-custom-keyword-iosproject.
 - Open katalon-custom-keyword-ios　Project and open Keywords folder and confirm you have a copy of the git repository keywords.
 - You can change project name via Project > Settings

[see the video on how to use custom keyword in a test](https://github.com/monstar-lab/katalon-custom-keyword-ios/blob/master/Add%20a%20coustom%20keyword%20to%20test1.mov)
