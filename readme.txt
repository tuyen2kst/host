# host
----------------------------------------------------------------
…or create a new repository on the command line
echo "# test" >> README.md
git init
git add README.md
git commit -m "first commit"
git log
git status
git branch -M master
git branch -M main
git remote rm origin
git remote add origin https://github.com/tuyen2kst/host.git

git remote rm origin
git remote rm freetuts

git pull remotename master:dev

git add --all
git commit -m "some message"
git pull remotename master:dev
git push remotename master:dev

git remote -v
git push
git push --force origin main
git push -u origin main


git push origin master
---------------------------------------------------------------
…or push an existing repository from the command line
git remote add origin https://github.com/tuyen2kst/host.git
git branch -M main
git push -u origin main
…or import code from another repository
You can initialize this repository with code from a Subversion, Mercurial, or TFS project.
