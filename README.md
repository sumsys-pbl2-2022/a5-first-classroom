# a5-1st-classroom
First GitHub Classroom Assignment

このプロジェクトは、システム工学応用実習II-2022の課題 A5用です。

ファイルの編集作業などは、ローカルで行います。

# 準備
- まず、このリポジトリをクローンしてローカルにリポジトリをつくります。

# ブランチdevの作成
- `git branch dev` としてブランチを作成し、`git checkout dev`として、ブランチdevでの作業を始めて下さい。

# hello.pyの編集とコミット、push
- hello.pyを編集して、`print("Hello Hamamatsu")` のようなコードを1行追加してください。
- `python3 hello.py`としてプログラムを実行し、正しく動くことを確認してください。
- それが終わったら、`git commit -a -m "あなたのコメント"`として編集結果をコミットしてください。
- その後、`git push --set-upstream origin dev`として、GitHubにあるリモートリポジトリに編集結果を反映させます。

# sum.pyの追加とコミット、mainへのマージ、push
- 次に、sum.pyという新しいファイルをつくり、以下のコードを加えて下さい。
```
num1 = 1.5
num2 = 6.3

sum = num1 + num2
print('The sum of {0} and {1} is {2}'.format(num1, num2, sum))
```

- sum.pyの動作を確認したら、編集結果をコミットしてください。
- ブランチ main に移って、ブランチdevの内容をマージして下さい。
- `git push`として、結果をGitHub上のリポジトリに反映させます。

# プルリクエスト

- `×××` として、結果をプルリクエストして下さい。
