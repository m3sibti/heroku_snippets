# Heroku Snippets
This is a guide to heroku launch of your website

1. Install `pip install gunicorn`
2. Create Procfile `vim Procfile -> web: gunicorn app:app`
3. Create req file `pip freeze > requirements.txt`
4. Intialize your repo `git init`
5. Add all files `git add .`
6. Add initial commit `git commit -am 'initial commit'`
7. Login on your heroku account `heroku login`
8. Create your application w.r.t Heroku `heroku create`
9. Rename your app according to project `heroku rename 'xyz'` or `heroku rename xyz --app previous_name`
10. Push your heroku app on console `git push heroku master`
11. After every change you have to `git add .` & `git commit -am 'new commit'`, then push
12. Check all apps using `heroku apps`
13. File access use `heroku run bash --app xyz`

<hr>
