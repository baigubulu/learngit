create a new repository on the command line
echo "# learngit" >> README.md
git init
git add read.txt
git commit -m "first commit"
git remot add origin https://github.com/baigubulu/learngit.git
git push -u origin master

...or push an existing repository from the command line
git remote add origin https://github.com/baigubulu/learngit.git
git push -u origin master

...or import code from another repository
you can initialize this repository with code from a Subversion, Mercurial,or TFS project.
