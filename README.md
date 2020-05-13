This buildpack installs the
[`pg-extras`](https://github.com/heroku/heroku-pg-extras) plugin for
`heroku-cli`. 

Usage: 

``` sh
heroku buildpacks:add heroku-community/cli
heroku buildpacks:add clerky/heroku-buildpack-pg-extras https://github.com/some/buildpack.git
```
