# kernel_relative
git clone git@github.com:chen45464546/kernel_relative.git

on a new shell steps to commit to this repo:
git config -l
git config --global user.name "chen45464546"
git config --global user.email "chen45464546@163.com"
git config -l

ssh-keygen -t rsa -C "chen45464546@163.com"
cat ~/.ssh/id_rsa.pub
copy it to web setting ssh key

git clone git@github.com:chen45464546/kernel_relative.git
 git staus
 ...
 git commit -m "test:first push test"
 git push -u origin master
 git pull
