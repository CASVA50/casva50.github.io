# Welcome to MkDocs

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Get the latest website pages 

To get the latest pages of the documentation please run :

* `git pull` 

This must be a mandatory before modifying the website.

## Publish on github

In order to publish after modifying/adding pages please run the following command :

* `mkdocs serve` - Preview - Start the live-reloading docs server.
* `mkdos buid` - Build the documentation site.
* `mkdocs gh-deploy` - Deploy the site 

Then push to github : 

```
git add * # you can also choose the file you want to add by specifing the path
git commit -m your_explanation
git push
```

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.

    