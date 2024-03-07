# Raspio

旗艦 io

## tips

raspi単体でエディタを動かすのでgitとかvimの練習するわ

### git 


```bash
# gitの基本的なコマンド

# commit
git commit -m "commit message"

# push
git push origin [main? master?]

# branch
## branchの作成
git branch [branch_name]
## branchの切り替え
git checkout [branch_name]
## branchの削除

# merge
git merge [branch_name]
## test branchからmain branchにmergeするには、
## main branchに切り替えてから
git merge test

# pull
git pull origin [main? master?]

# fetch
git fetch origin [main? master?]