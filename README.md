echo "# Как пользоваться Git" > README.md 
echo '* Перед коммитом изменений нужно убедиться, что все файлы добавлены в индекс.' >> commmit_help.md
echo '* Посмотреть состояние индекса можно командой `git status.`' >> commmit_help.md
echo '* Используйте `git add filename` для добавления конкретного файла или `git add .` для добавления всех файлов' >> commmit_help.md
echo '* Чтобы одной командой добавить все изменённые файлы и сделать коммит, выполните `git commit -am "commit message"`' >> commmit_help.md
echo '* Новые файлы добавлены не будут' >> commmit_help.md
echo '- [Как сделать новый коммит](./commmit_help.md)' >> README.md

echo "Команда checkout используется в Git, чтобы:" > branch_help.md
echo "* переключиться на произвольную существующую ветку (git checkout branch-name)" >> branch_help.md
echo "* создать новую ветку от текущей (git checkout -b new-branch-name)" >> branch_help.md
echo '- [Ветвление](./branch_help.md)' >> README.md
