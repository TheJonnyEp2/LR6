# LR6
Лабораторная работа №6

__Цель лабораторной работы:__ изучение базовых возможностей системы управления версиями, получение опыта работы с Git Api, опыта работы с локальным и удаленным репозиторием.

__Клонирование репозитория на компьютер__

![Клонирование репозитория](./screenshots/clone.png)

__Добавление файла в репозиторий средствами GitHub__

![Добавление текстового файла](./screenshots/text.png)

__Подтягиваем изменения в локальный репозиторий__

![pull](./screenshots/pull.png)

__История операций для ветки master__

![masterlog](./screenshots/log1.png)

__История операций для ветки branch1__

![branch1log](./screenshots/log2.png)

__Попытка слияния__

![merge](./screenshots/merge.png)

__Разрешение конфликта слияния__

В процессе разрешения конфликта слияния было принято решение изменить mergefile.txt в master, как он представлен в ветке branch1

![fixmerge](./screenshots/merge_fix.png)

__Коммит о слиянии веток__

![mergecommit](./screenshots/merge_commit.png)

__Удаление ветки__

![branchdelete](./screenshots/delete_branch.png)

__Создание ветки для отчёта__

![branchcreate](./screenshots/branch_create.png)

__Добавление папки со скриншотами в репозиторий__

![foldercreate](./screenshots/folder_screenshots.png)

Лог команд:
```
git clone https://github.com/TheJonnyEp2/LR6.git  - клонирование репозитория на компьютер
cd LR6/  - переход в папку репозитория
git pull  - подтягивание изменений
git log origin/branch1  - получение истории операций для ветки branch1
git merge branch1  - слияние с веткой branch1
git commit -m "Merged branch1"  - коммит об успешном слиянии
git branch --delete branch1  - удаление ветки branch1
mkdir screenshots - создание папки
git status  - получение статуса репозитория
git commit -m "подпись и скриншоты"  - коммит
vim the_file.txt  - изменение файла the_file.txt
git revert 6bd43e0  - откат коммита
git commit -m "reverted the_file.txt modification"  - коммит об откате коммита
git push --set-upstream origin report - создание новой ветки и переход на неё
git switch report  - переключение на ветку отчёта
```

История операций:
```
ed4f6d8 2024-10-28 TheJonnyEp2 подпись и скриншоты
a158e86 2024-10-28 TheJonnyEp2 финальная(надеюсь) попытка добавления ссылки
5a12924 2024-10-28 TheJonnyEp2 четвертая попытка добавления ссылки
07fc92f 2024-10-28 TheJonnyEp2 третья попытка добавления ссылки
b1796f5 2024-10-28 TheJonnyEp2 вторая попытка добавления ссылки
9cf0808 2024-10-28 TheJonnyEp2 попытка добавления ссылки
19ef22b 2024-10-28 TheJonnyEp2 пробная попытка оформления отчёта
1dcf060 2024-10-23 TheJonnyEp2 Merged branch1
372eeec 2024-10-23 TheJonnyEp2 Create The_file.txt
921f53b 2020-11-21 GitHub Обновление информации
0f9f50d 2020-11-21 GitHub Заполнил файл
c08a654 2020-11-21 GitHub Файл создан пустым
3c6e913 2020-11-21 GitHub Initial commit
```

__Вывод:__ Я изучил базовые возможности системы управления версиями, получил опыт работы с Git Api, опыт работы с локальным и удаленным репозиторием.