# touchviewer-documentation

#### Site Generator
[MkDocs](https://www.google.com)<br>
[Material for MkDocs](http://squidfunk.github.io/mkdocs-material/)

#### Deploy
Add "site" folder in .gitignore<br>
* `git add site -f && git commit -m "init subtree"`<br>
* `git subtree push --prefix site origin gh-pages`<br>

#### Shortcut
Add in .git->config<br>
* `[alias]<br>
deploy = subtree push --prefix site origin gh-pages`<br>
To use<br>
* `git deploy`
