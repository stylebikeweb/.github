ISSUE-and-PR-templates
============================================
組織の Issue と Pull Request 作成用のテンプレート



個別カスタマイズ方法、めっちゃ簡単〜！  
--------------------------------------------
個別リポで独自のカスタマイズは...

個別リポに独自の .github フォルダを作るだけでOK！  
同じ名前のテンプレファイルを置くと、個別リポのほうが優先されちゃう！  
必要なテンプレだけ上書きできるから、一部だけカスタマイズもOK〜  

例えば、組織レベルで共通のバグレポートテンプレ使いつつ、特定のリポだけ別の PR テンプレ使いたい場合とか：

```
個別リポ/
  .github/
    PULL_REQUEST_TEMPLATE.md  <- このリポ専用のPRテンプレ！
```
他のテンプレは組織の .github リポから拾ってくれるから、めっちゃ便利〜！😘

<!-- TODO: テンプレートを追加
Issue URL: https://github.com/stylebikeweb/ISSUE-and-PR-templates/issues/1
 - ISSUE_TEMPLATE
   - bug-report.yaml
   - feature-request.yaml
 - PULL_REQUEST_TEMPLATE 
-->
