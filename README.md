config order:

create new repo

> git clone {html}

add file contents to cloned folder (do NOT push yet)

> bundle install

> bundle exec jekyll build

> bundle exec jekyll serve (check local build works)

> bundle lock --add-platform x86_64-linux

> git add --all 

> git commit -m 'add files' 

> git push

Go to github repo -> settings -> pages -> github actions -> configure yml and save


check progress in actions tab
