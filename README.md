# git
git configs, shortcuts and helpers

[![GitHub Last Commit](https://img.shields.io/github/last-commit/curtisdingdong/git?logo=github)](https://github.com/curtisdingdong/git/commits/master)
[![Markdown Lint](https://github.com/curtisdingdong/git/actions/workflows/markdown.yaml/badge.svg)](https://github.com/curtisdingdong/git/actions/workflows/markdown.yaml)
[![Yaml Lint](https://github.com/curtisdingdong/git/actions/workflows/yamllint.yaml/badge.svg)](https://github.com/curtisdingdong/git/actions/workflows/yamllint.yaml)

## Deleting Local Branches

git branch -d branchname (deletes branch if it has already been fully merged in upstream branch)
git branch -D branchname (alis for --delete --force, deletes branch regardless of merged status.)

## Deleting remote branches

git push REMOTENAME --delete BRANCH

## Deleting commits on remote 

git reset --hard HEAD~3

## delete the comits from remote

git push origin HEAD --force