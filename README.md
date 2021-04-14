# OfficeWorkManual
事務マニュアル

Git上の追加分の記載について学習中、まだわからんこと結構ある</br>
➊Gitの領域について
## ★ローカルリポジトリ
  パソコン内部に保存されているフォルダで保管庫の意味で【リポジトリ】という名前になっている。</br>
  リポジトリ化すると隠しフォルダの.gitが作られる。</br>
### ★リポジトリ化したフォルダ内の二つの世界
  ➀Git外からでも操作できる【ワーキングディレクトリ】＝主に編集しているときは、これを編集している。</br>
  ➁Gitが管理する【リポジトリ(.gitフォルダ)】で、セーブデータ(その都度コミットしたバージョン)を複数記録、保存している。</br>
  ※注意：これを見るためにはGitに対応したアプリでしか見ることができない</br>
  ◎対応アプリ例：GitHub Desktop</br>
## △リモートリポジトリ
➋Gitの主な操作用語
### ★コミット
  リポジトリ(gitフォルダ)に記録する操作のことで、それまでの操作をセーブするようなイメージ。</br>
  これを行うことで、再度編集して記録という作業を何度も行うことができる。</br>
  ※注意：いったんコミットしたデータは消せないので、コミットする内容にはくれぐれも慎重に</br>
  ◎NGコミット内容:個人情報・パスワードetc</br>
### △プッシュ
  現在のローカルリポジトリの内容をリモートリポジトリに反映させる操作のこと。</br>
  これによって、自分が行った作業をリモートリポジトリを通じて他のメンバーに共有できる。</br>
### △プル
  リモートリポジトリの変更を取得して、自分のローカルリポジトリに反映させる操作のこと。</br>
  プッシュとは逆で、現在自分が所持してるローカルリポジトリが古い可能性があり、他のメンバーの変更点を更新するため。</br>
➌Gitにおけるエラーについて
## コンクリフト(衝突)
  【事象場面】複数人がローカルリポジトリ内で編集作業を行っている場合に起こる。</br>
  【事象原因】複数人が同じファイルをプッシュした場合、同じファイルの内容が食い違っていることによって発生する。</br>
### 〘対処方法〙
  1.チャットツールで事前に編集するファイルを分担しておくこと。
