git status - получить статус файлов
git add [files] || . - добавляет файлы в stage
git commit -m "чегонить" - делаем комит
git log - смотрим логи
git log --oneline - смотрим краткие логи
git push [rep_link] [branch_name] - заливаем на удаленный репозиторий
git push origin master - ( через git remote -v выбираем url и branch)

git reset file.ext - можно удалить файлы из промежуточной области (stage)
git reset --hard - возвращает файлы к тому что было до изменений
git diff - посмотреть что жобавляли удаляли в файлах
git diff file.ext - посмотреть что жобавляли удаляли в конкретном файле

gitignore (список файлов не добавляющиеся в удаленный репозиторий)
