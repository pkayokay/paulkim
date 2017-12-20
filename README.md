# Blog Site

Personal blog site built on [Rails](http://www.rubyonrails.org) and [Spina CMS](http://www.spinacms.com).

## Environments
* https://devcenter.heroku.com/articles/multiple-environments

		heroku create app-dev --remote dev
		heroku create app-prod --remote prod
		heroku run rails db:migrate —app app-prod

		git push [environment] [branch you want to push]
		git push dev develop:master
		git push prod master:master

### Github branches: 
* `develop`
* `master`

### Heroku
* `dev`
* `prod`