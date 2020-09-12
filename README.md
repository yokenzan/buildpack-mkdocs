# MKdocs builder && Static runner

This buildpack is for deploying [Mkdocs](https://www.mkdocs.org/) static sites to [Heroku](https://www.heroku.com/).

This buildpack works well only when used with [heroku-buildpack-static](https://github.com/heroku/heroku-buildpack-static) and [heroku-buildpack-python](https://github.com/heroku/heroku-buildpack-python).

You need to prepare `static.json` to publish with heroku-buildpack-static and `requirements.txt` to install dependencies including Mkdocs with heroku-buildpack-python.

```bash
# Heroku:
heroku buildpacks:set heroku/python
heroku buildpacks:add https://github.com/yokenzan/buildpack-mkdocs
heroku buildpacks:add https://github.com/heroku/heroku-buildpack-static.git
```
