
# [<===](/index.md)

Проверяем путь   
## pwd

проверяем инецыолизирован или нет   
## git status

если нет иницылезируем   
## git init

добовления в индекс
## git add

создания камита 
## git commit -m "commot 01"

откат изменений до начал комита
## git checkout -- test.md

посмотреть историю комитов репозитория 
## git log

выводит коммит на одной строке, содержащей только его хеш и первую строку сообщения
коммита
## git log --oneline

рисует ASCII-граф истории коммитов, показывая ветвления и слияния
## git log --graph

--all выводит все доступные коммиты в
репозитории
## git log --all

Используется для переключения между ветками, восстановления файлов из индекса или рабочего каталога, а также создания новых веток.
## git checkout -- (имя файла и тип) отменить изменения
## gti checkout (хеш комитта) переключение  на определенный коммит изменения

## git checkout (имя ветки) переключение между ветками

рекоминдовано 
## git switch (имя ветки) перключения между ветками 
## git switch -с (новая ветка) примечанеи создания ноаой ветки и переключения на нее
## get switch (имя ветки) примечания лучше использовать переключится на данную ветку
## git switch -d (имя ветки) удаляет ветк
## git switch (хеш комита) переключается на определенный комит 

## get restore --stage (Фаил) востоновления файла из индекса

## git switch (файл и  тип его) востоновления файла из предведушего каммита

## git branch список всех веток
## git branch -b (имя новой ветки) примечание создания новой ветки и преключения на неё
## git branch -d (имя ветки) примечание устарел удаляет ветку
## git branch -D (имя ветки) примечание устарел удаляет ветку даже если небыла слита
## git branch -M (имя ветки) переименовать ветку
## git branch -m (имя ветки) примечание не будет перезаписанноа если внесинны изменения 
## git branch (имя новой ветки)примечане не переключает на неё
## git branch -D (имя ветки) удляет ветку дажи если она не была сллита с другими ветками 
## git checkout (имя ветки) примечания для переключения

## git merge используется для объединения изменений из одной ветки в другую. Обычно это делается для включения изменений из одной ветки (исходной) в текущую ветку (целевую).