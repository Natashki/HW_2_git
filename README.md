# HW_2_git
GitHub. HW_2
1. На локальном репозитории сделать ветки для:
- Postman  
- Jmeter
- CheckLists
- Bag Reports
- SQL
- Charles
- Mobile testing

>git branch Postman\
>git branch Jmeter\
>git branch CheckLists\
>git branch Bag_Reports\
>git branch SQL\
>git branch Charles\
>git branch Mobile_testing

2. Запушить все ветки на внешний репозиторий
>git push origin --all

3. В ветке Bag Reports сделать текстовый документ со структурой баг репорта
>git chekout Bag_Reports\
>touch bug_report_1.txt\
>vim bug_report_1.txt

4. Запушить структуру багрепорта на внешний репозиторий
>git add .\
>git commit -m "add bug_report_1"\
>git push --set-upstream origin Bag_Reports

5. Вмержить ветку Bag Reports в Main
>git checkout main\
>git merge Bag_Reports 

6. Запушить main на внешний репозиторий.
>git commit -ma "add bug_report_1 to main"\
>git push
 
7. В ветке CheckLists набросать структуру чек листа.
>git chekout CheckLists\
>touch check_list_1.txt\
>vim check_list_1.txt

8. Запушить структуру на внешний репозиторий
>git add .\
>git commit -m "add check_list_1"\
>git push --set-upstream origin CheckLists

9. На внешнем репозитории сделать Pull Request ветки CheckLists в main

10. Синхронизировать Внешнюю и Локальную ветки Main
>git pull