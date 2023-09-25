# Budget_Management-

このリポジトリは、予算管理アプリを作成するためのものである.

# 目的
電通大deラボでは，毎月それなりの額の予算を利用している．<br>
しかしながらそれらの予算が何にいくら利用され，どれだけ余ったか，足りていないのかを管理する仕組みが現状不足している．<br>
従って以下のような機能を持つWebアプリを作成し，この仕組みづくりを実現する．<br>

# 機能
**予算申請機能**<br>
  プロジェクトごとに毎月申請<br>
  ・プロジェクト名<br>
  ・申請者 <br>
  どの項目にどれだけの予算が必要かを入力する．これらは複数存在する<br>
  ・項目<br>
  ・単価<br>
  ・個数<br>
  ・備考<br>
  ・（項目IDを付与する）<br>
**発注申請機能**<br>
  項目IDに対して発注を申請する<br>
  申請内容<br>
  ・申請者<br>
  ・項目ID<br>
  ・購入先（URL or 店舗名）<br>
  ・単価<br>
  ・個数<br>
  ・フラグ：購入済 or 購入予定 or 購入依頼<br>
**分析機能**<br>
  項目IDごとにいくら余っているのか，オーバーしているのか<br>
  プロジェクト単位でいくら余っているのか，オーバーしているのか<br>
  月単位での収支<br>

また、機能に関するER図は以下のリンクにある.(GitHubアカウントが必要)<br>
https://app.diagrams.net/#HUECdeLAB%2FBudget_Management-%2Fmain%2FERDiagram

