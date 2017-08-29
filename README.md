google-app-engine-ranklist-ndb
==============================

**[https://leaderboard-api-178317.appspot.com/](https://leaderboard-api-178317.appspot.com/)**

google-app-engine-ranklist-ndb is a forked project from https://code.google.com/p/google-app-engine-ranklist/

Following changes are made to the original code

* use ndb instead of raw datastore
* get_score function with player name
* basic test code

This project include example server code from original repository. run ```dev_appserver.py example``` to start example code.


About Ranklist
==============

Ranklist is a python library for Google Appengine that implements a
data structure for storing integer scores and quickly retrieving their
relative ranks.

See the docstrings in ranker/ranker.py for more details and usage
examples.


Example
=======

An example application can be found in the "examples" directory. You
can run it with the following command:

$ dev_appserver.py example

Commands
======

```
gcloud config set project leaderboard-api-178317
gcloud app deploy app.yaml
```

Resources
======

- [Github uberik/google-app-engine-ranklist](https://github.com/Ruberik/google-app-engine-ranklist)
- [Github ymorired/google-app-engine-ranklist-ndb](https://github.com/ymorired/google-app-engine-ranklist-ndb)
- [Official code for google-app-engine-ranklist](https://code.google.com/archive/p/google-app-engine-ranklist/source)
- [Fast and Reliable Ranking in Datastore](https://cloud.google.com/datastore/docs/articles/fast-and-reliable-ranking-in-datastore/)
- [Google App Engine Blog](http://googleappengine.blogspot.jp/2009/01/google-code-jams-ranking-library.html)