# Branches
GitHub. HW_2
1. На локальном репозитории сделать ветки для - git branch name
- Postman
- Jmeter
- CheckLists
- Bag Reports
- SQL
- Charles
- Mobile testing

2. Запушить все ветки на внешний репозиторий - git push origin name
3. В ветке Bag Reports сделать текстовый документ со структурой баг репорта git checkout Bug_reports > nano bug_report.txt > save
4. Запушить структуру багрепорта на внешний репозиторий - git add . > git commit -m "commit for bug report" > git push origin main
5. Вмержить ветку Bag Reports в Main - git checkout main (если мы находились в ветке Bug_reports) > git merge Bug_reports
6. Запушить main на внешний репозиторий. git push origin main
7. В ветке CheckLists набросать структуру чек листа. - Переходим в ветку Checklist > nano checkl.txt > save
8. Запушить структуру на внешний репозиторий - git add checkl.txt > git commit checkl.txt > git push origin Checklists
9. На внешнем репозитории сделать Pull Request ветки CheckLists в main > переходим в вебе в ветку Checklist > Сompare&Pull request > Create pull request > Merge pull request
10. Синхронизировать Внешнюю и Локальную ветки Main > git checkout main > git pull
