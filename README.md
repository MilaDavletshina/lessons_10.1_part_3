# Задача
## Сделайте пул-реквест и разрешите конфликт.
   Для этого выполните следующие шаги:
- Создайте локальный проект и три ветки: main, develop, feature.
  Cоздаем новый проект в pycharm-vcs-create git repository-добавляем файл main.py
  весь проект git-add-git-commit.
  Добавляем ветку develop и feature/task-1
- Создайте удаленный репозиторий и отправьте туда ветки main и develop локального репозитория.
  переключаемся на ветку main-
  в удаленном репозитории создаем новый репозиторий-копируем SSH путь и добавляем в pycharm -git—manage remote вставить SSH путь
  git-push
  переключаемся в ветку develop-git-push
- Сделайте такую ситуацию, чтобы при пул-реквесте из функциональной ветки в ветку develop на удаленном репозитории случился конфликт.
  вносим изменения в main.py в pycharm в ветку develop-commit-push
  переключаемся в ветку feature/task-1 и вносим изменения в main.py-commit-push
  делаем pull request в GitHub-pull request-create and pull из ветки develope в feature/task-1 появляется конфликт. Pull request создается, но сделать merge не возможно
- Решите конфликт локально и снова сделайте пул-реквест на GitHub. На этот раз всё должно пройти.
  переходим в pycharm-нужно влить develop в feature/task-1 с помощью git-merge-выбираем ветку develop-merge-merge-переносим все в середину-решаем конфликт-apply-git-push
  переходим в github и делаем merge pull request-confirm merge
- Получите актуальное состояние ветки recent develop  в локальном репозитории.
  переключаемся в develop-git-update project
