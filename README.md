### rest your branch to commit hash
let say you have branch main and you have 3 commits there. now say you want to reset it to initial commit with 7825011282b5896b8910547e06efd5519076c353
```shell
git reset --hard 7825011282b5896b8910547e06efd5519076c353
git push origin main --force
git log # to verify it wil only show commits where we reset it. 
```

intellj same thing git> log > select branch > commit you want to reset this brach > select hard reset and then push it.
Note : it intellij keep history of commit still .

