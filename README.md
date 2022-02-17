$ rm -rf dist
$ echo  " dist/ "  >> .gitignore
$ git worktree add dist gh-pages
Внесение изменений
$ make # или что бы вы ни запускали для заполнения dist
$ cd dist
$ git add --all
$ git commit -m " Deploy to gh-pages "
$ git push origin gh-pages
$ cd ..
