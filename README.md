# temple-du-swing.github.io

TODO

## Local developpement

Fisrt, update the data from contentful (Headless CMS) with the following commande:

```sh
set -o allexport; source .env; set +o allexport; bundle exec jekyll contentful
```

Then, launch the server:

```sh
bundle exec jekyll serve
```

## Sample

Voir le site du gouvernement comme exemple [ici](https://github.com/github/government.github.com).
