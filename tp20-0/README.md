#   tp20.0

##  Build Instructions

With Docker Compose:

```bash
# Site:
$ docker-compose run --rm tp20-0 make site
# PDF:
$ docker-compose run --rm tp20-0 make pdf
```

With pip and stuff (requires Python 3.6+, Pandoc, and TeXLive):

```bash
$ pip install -r requirements.txt
# Site:
$ foliant make site
# PDF:
$ foliant make pdf
```
