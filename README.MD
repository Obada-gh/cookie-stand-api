# Back-End-Deployment

Heroku:
create Heroku.yml at first , then 
1. git init
2. heroku apps:create <app_name>
3. git add .
4. git commit -m ""
5. git remote add origin <repo's link from github>
6. heroku ps
7. heroku stack:set container
8. gunicorn <project_Name in VS code>
9. git push origin master
10. git push heroku master
11. add the cofig keys in setting in the app .
