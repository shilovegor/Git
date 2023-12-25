# 📌 Git

Git — это система контроля версий, доступная на компьютере каждого разработчика. Это позволяет легко разветвлять и объединять. В то же время GitHub значительно упрощает использование Git для контроля версий и совместной работы отдельными людьми и командами 🤝

Я рад поделиться некоторыми командами git, которые я использовал для создания своего портфолио на GitHub. 


## Task 1

##### Создание, клонирование, отправка и извлечение репозиториев 
```git
git init shilovegor                                        # Создайте свой репозиторий с тем же именем, что и ваше имя пользователя. 
git clone git@github.com:githab/shilovegor.git        # Клонируйте репозиторий на своем компьютере в отдельную папку.
git clone git@github.com:testrusau/testrusau.git            # Клонируйте github.com/testrusau/testrusau на своем компьютере в отдельную папку.
cd testrusau                                                # Перенесите данные из репозитория testrusau в свой собственный. 
git push git@github.com:githu/testrusau.git main:main
git commit -m "new commit"                                  # Откройте файл README.md и замените каждый блок отдельным коммитом.
git push 

```
## Task 2

##### Создание, добавление удаленных репозиториев  
```git
git init sql                                                # Создайте отдельный репозиторий для элемента портфолио. 
git remote add sql https://github.com/rustamfox23/sql.git   # Объявить репозиторий удаленно 
README.md                                                   # Добавьте ссылки на ваши репозитории в файл README.md
git commit -m "commited change description"                 # Отправить изменения в удаленный репозиторий
git push                                                     




```
