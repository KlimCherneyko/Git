# 📌 git

Я рад поделиться некоторыми командами git, которые я использовал для создания своего портфолио на GitHub. 

## Easy navigation

- [Создание, клонирование, отправка и извлечение репозиториев](#task-1)
- [Создание, добавление удаленных репозиториев](#task-2)

## Task 1

##### Создание, клонирование, отправка и извлечение репозиториев  
```git
git init osukhorukova                                       # Create your repository with the same name as your username 
git clone git@github.com:osukhorukova/osukhorukova.git      # Clone your repository on your computer to a separate folder
git clone git@github.com:testrusau/testrusau.git            # Clone github.com/testrusau/testrusau on your computer to a separate folder
cd testrusau                                                # Push data from testrusau repository to your own one 
git push git@github.com:osukhorukova/testrusau.git main:main
git commit -m "commited change description"                 # Open the README.md file and replace each block with a separate commit 
git push 

```
## Task 2

##### Создание, добавление удаленных репозиториев  
```git
git init sql                                                # Create separate repository for portfolio item 
git remote add sql https://github.com/osukhorukova/sql.git  # Declarie repository remotely 
README.md edited manually                                   # Add links to your repositories to the README.md file
git commit -m "commited change description"                 # Push changes to remote repository
git push                                                     




```