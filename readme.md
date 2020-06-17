### upload
dodawanie do kolejki (stage):
> git add .

wstawienie commita (czyli zatwierdzenie zmian)
> git commit -m "komentarz do commita"

i sam upload tego commita na mastera:
> git push origin master
### ściąganie do siebie (nadpisuje zmiany)

> git pull origin master


## Tworzenie repozytorium z istniejącego już folderu
Create a new repository on GitHub. You can also add a gitignore file, a readme and a licence if you want
 
Open Git Bash
Change the current working directory to your local project.

Initialize the local directory as a Git repository.
> git init

Add the files in your new local repository. This stages them for the first commit.
> git add .

Commit the files that you’ve staged in your local repository.
> git commit -m "initial commit"

Copy the https url of your newly created repo
In the Command prompt, add the URL for the remote repository where your local repository will be pushed.

> git remote add origin https://github.com/Dziarrr/1repodonaukigita.git

> git remote -v

Push the changes in your local repository to GitHub.

> git push -f origin master

That’s all :)
