# Heroku Buildpack PrinceXML

A buildpack that installs PrinceXML on Heroku.

Default version is 11.4.

Set $PRINCE_VESION to another valid version to over-ride this (`heroku config:set PRINCE_VERSION`)

Set your license file to $PRINCE_LICENSE (`heroku config:set PRINCE_LICENSE`)

This buildpack caches the output between runs to speed up deployment. If you need to clear the cache for some reason use the [heroku-repo plugin](https://github.com/heroku/heroku-repo#purge-cache)
