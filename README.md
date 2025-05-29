# Quarkus demo: Hibernate ORM with Panache and RESTEasy

[Launch in Dev Spaces](https://devspaces.apps.prime.pitt.ca/f?url=https://github.com/pittar-sandbox/quarkus-postgres-continue)

This is a minimal CRUD service exposing a couple of endpoints over REST,
with a front-end based on Angular so you can play with it from your browser.

Dev Spaces is pre-configured to install the [Continue.dev]() extension.  It expects a "config.json" file to be mounted at `/data/config/continue`.  There is a postStart event hook in `devfile.yaml` that will then copy it to the correct location to configure Continue.

