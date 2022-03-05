# Handy-Commands
A repo I use as an extension of my mental memory

## git
* git reset --soft HEAD~1 _//unstage your last commit_
* git reset --soft <commit> _//specify the commit hash_
* git push origin <your_branch_name> --force _//make what you have locally gospel_
* git remote add origin <url>
* git push --force _//handy when deleting the last remote commit

## Django
* python3 manage.py runserver _//start server_
* python3 manage.py makemigrations; python3 manage.py migrate _//sync with database_
* ./manage.py shell < server/testscript.py _//run py scripts manually_
* python3 manage.py shell _//can use sqlite from here too_
* python3 manage.py createsuperuser
                                          
## SQlite3
* sqlite3  db.sqlite3
* SELECT * FROM server_world;
* .headers on _//show column names for querys_
