#Githubをcuiでやるメモ
(さっさと覚えたいと思います)
##初期設定
```
$ sudo apt install git
$ git config --global user.name "Ryuichi Ueda"
$ git config --global user.email "ueda@hogehoge.com"#
$ git config --global core.editor vim
```
##addしてstatusみてcommit,push
```
$ git add -A #全部addする
$ git status
$ git commit -m "なんかしらのコメント"
$ git push
```

##branch
```
$ git branch #ブランチ確認
$ git checkout -b hoge #hogeブランチ作成
$ git checkout hoge #hogeブランチ変更
$ git merge hoge 
