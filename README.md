# Шпаргалка с командами гита

---
## Навигация
* `pwd` - Выводит путь нынешней директории
* `ls` - Выводит все файлы в нынешней папке 

   с флагом `ls -a` выведет *дополнительно* скрытые папки и файлы
* `cd /first-project` - Переход в папку *first-project*

  `cd ..` - Переход на папку выше  
  `cd ~` - Переход в домашнюю директорию

---
## Работа с файлами и папками
### Создание, удаление, перемещение
* `touch draft1.txt` - Создает файл *draft1.txt*
* `mkdir dev` - Создает папку *dev*
* `rm draft1.txt` - Удаляет файл *draft1.txt*
* `rmdir dev` - Удаляет папку (**если пустая**)
* `rm -r dev` - Удаляет папку вместе с содержимым
* `cp draft1.txt ~/Desktop` - Копирует файл в указанную папку
* `mv draft1.txt ~/git1` - Перемещает файл в указанную папку

---
## Работа с github
* `git init` - Инициализация репозитория в нынешней папке
* `git remote add origin git@github.com:...` - Привязка локального репозитория к удаленному  
   `git remote -v` - Просмотр соединений локального репозитория с удаленным
* `git status` - Просмотр изменений в репозитории
* `git add --all` - *Запоминание* содержимого всех файлов
* `git commit -m "Комментарий"` - *Сохранение* в историю изменений файлов
* `git log` - История коммитов
* `git push main/master` - Загрузка файлов на удаленный репозиторий  
   `git push -u origin master/main` - __При первом push нужно использовать эту команду__ 
* __to be continued...__