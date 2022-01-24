# Deploying Task Changes

Changes to the /tasks folder need to be copied to the database copied to the app and to the user-friendly site.

* Run `make build_db` from within `../tools/database/` to replace the database artifact deployed with the app.

* Run `python tasktoweb.py` from within `../tools/tasktoweb/` to update the public site with task changes.