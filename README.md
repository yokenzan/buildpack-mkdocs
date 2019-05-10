# MKdocs builder && Static runner

```bash
# Heroku:
heroku config:set BUILDPACK_URL=https://github.com/anerhan/buildpack-mkdocs
heroku config:set BUILDPACK_URL=https://github.com/heroku/heroku-buildpack-static.git
```

- Works Only together with ```https://github.com/heroku/heroku-buildpack-static.git```
