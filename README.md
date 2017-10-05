## Deploy

```
heroku login
git remote add heroku https://git.heroku.com/smalltalk-site.git
yarn build
git add .
git commit -am "<msg>"
git push
git push heroku master
```