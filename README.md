# Practice_GensoBall
Gitの使い方練習用

gitのコマンド
・clone
・pull
・branch
・checkout
・add
・commit
・push

コンフリクトの解消法(ブランチXXがコンフリクトを起こしたとき)
1　自分のローカル環境のmasterに、リモートのmasterをpullする
    $git checkout master
    $git pull

2　コンフリクトを起こした自分のbranchにcheckoutして、自分のmasterをマージする
    $git checkout ブランチXX
    $git merge master

3　VScodeなどを利用し、コンフリクトしている部分を解決

4　変更をリモートリポジトリへ反映
    $git add --all
    $git commit -m ""
    $git push origin ブランチXX