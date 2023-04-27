Home Assistant Blueprints
=========================
This repo contains various custom blueprints I use for [Home Assistant](https://www.home-assistant.io/getting-started).  
Not everything I use is public, but I try to make sure most of it is.

Blueprints In Repo
------------------
Currently, the following blueprints are in the repo:

1. [Offline Entities Alert](blueprints/offline_entities_alert) - Alert when any entity goes offline
2. [Grid Undervolted Alert](blueprints/grid_undervolted_alert) - Alert when a Tesla Wall Connector detects low voltage from the power grid.

pre-commit
----------
This repo uses Yelp's [pre-commit](https://pre-commit.com/) to manage some pre-commit hooks automatically.  
In order to use the hooks, make sure you have `pre-commit` in your `$PATH`.  
Once in your path you should run `pre-commit install` in order to configure it. If you push commits that fail pre-commit, your PR will
not pass tests.
