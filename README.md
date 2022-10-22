# main-git-commands
main commands git

git config —list -  показывает все настройки  репозитория

cd ~/Desktop - переход в папку

mkdir my-project - создание новой папки

cd my-project - переход в папку

echo "Some text" > file.txt - создание файла с текстом

pwd - посмотреть абсолютный путь к папке

ls - список файлов в папке

cat file.txt - чтение файла

rm file.txt - удаление файла

git status - отображает текущее состояние git репозитория

git add <files> - подготовить файл перед коммитом
  
git add . - подготовление изменения в индекс в проекте для последующего коммита
  
git commit -m "message" - сохранить изменения в репозиторий
  
git checkout <commit hash>  - перейти к определенной версии проекта по SHA1 хэшу коммита
  
git log - просмотр истории изменений (коммитов)
  
git checkout <branch name> - переход в другую ветку
  
git cat-file -t <SHA1 HASH"> - посмотреть тип файла
  
git cat-file -p <SHA1 HASH"> - чтение файла
  
cd .. - выйти из папки на уровень выше
  
git branch <branch name> - создание новой ветки
  
git checkout -b <branch name> - создание и переход в новую ветку
  
git branch - список веток в локальном репозитории
  
git branch -m <new branch name> - переименовать текущую ветку
  
git branch -d <branch name> - удалить ветку(не находясь в ней)
  
git merge -m <"message"> <feature branch name> - слияние другой ветки (feature branch) в текущую ветку (receiving branch)
  
code .  - открыть проект в редакторе кода visual studio

git clone <url> - клонирование удаленного репозитория через URL

git branch -a - посмотреть все ветки (удаленный репозиторий + локальный)

git pull - загрузка и применение изменений с удаленной ветки в локальную

git push - загрузка изменений из локальной ветки в ветку удаленного репозитория
