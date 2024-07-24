## Poetry

https://python-poetry.org/docs/#installing-with-the-official-installer

```bash
cd gph-site

poetry install
poetry run ## todo
```

## Notes

Copied from old gph-site

1. upgrade from local sqlite DB to be more production-ready (jeffery) also set secret_keys when doing so
2. setup on a subdomain of neshunt.com
3. talk to art team at some point
4. understand limitations of gph-site and document mising features to add (jeffery)


if move gph-site folder, change:
- /etc/systemd/system/gunicorn.service

if move venv folder, change;
- /etc/systemd/system/gunicorn.service

access-logifile in gunicorn.service currently none?
maybe add other logfiles?

Administrative details in: `admin-notes.txt`