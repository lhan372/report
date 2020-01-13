mkdir alice.github.com
cd alice.github.com
git init
git branch -m master gh-pages <- renames the "master" branch to "gh-pages"
echo "<h1>Hello Alice</h1>" > index.html
git add index.html
