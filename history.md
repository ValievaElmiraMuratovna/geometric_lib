# “Отчет о проделанной работе”
### “Автор: Валиева Эльмира”
[Ссылка на репозиторий с уроком про животных](https://github.com/ValievaElmiraMuratovna/wild_animals)

#### “Ход работы”

* cd Desktop/
* git clone https://github.com/smartiqaorg/geometric_lib
* cd geometric_lib
* git checkout develop
* git checkout release
* git log --all --pretty=oneline --graph
* git checkout main
* git merge develop --no-ff
* git reset --hard HEAD^
* git merge develop --ff
* git checkout release
* git rebase -i main
* git mergetool
* git rebase --continue
* git checkout main
* git merge release --ff
* git push --all git@github.com:ValievaElmiraMuratovna/geometric_lib.git
* ssh-keygen -t rsa -b 4096 -C 'el.gumerowa6@yandex.ru'
