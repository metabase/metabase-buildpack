# NOTE: the Heroku Buildpack release artifact will no longer be maintained by Metabase, as we strongly encourage everyone to either deploy in Heroku via containers or fork this repository. Please see announcement https://www.metabase.com/releases/Metabase-0.45

Heroku Buildpack for Metabase

Add the following to your app.json:

"buildpacks": [
  {
    "url": "https://github.com/metabase/metabase-buildpack"
  }
]
