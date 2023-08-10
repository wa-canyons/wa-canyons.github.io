config order:

create new repo
git clone html

add file contents to cloned folder (do NOT push yet)
bundle install

bundle exec jekyll build

bundle exec jekyll

bundle lock --add-platform x86_64-linux

git add --all git commit -m 'add files' git push

Go to github repo -> settings -> pages -> github actions -> configure
check progress in actions tab
