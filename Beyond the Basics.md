## Part 3 Beyond the Basics

Now that we know how to create a package, things are starting to get interesting. The problem with the last article is that if you do lots of package development, it can get tiring to repeat making the folder structure adding files manually, etc.

In this article I will talk about some of the tooling which can alleviate some of these repetitive tasks, by using other pip packages.

Tools:
- cookiecutter
- twine
- sdist
- bdist_wheel

# Cookiecutter
Getting hungry? Cookiecutter is an awesome cmd utility, it can clone a folder structure from another repository. It also assists with creaing the setup file straight from the terminal.

The cool thing about cookiecutter is that it creates all the needed files for a pypi package, readme, license, and all the other files.

- [cookiecutter repo](https://github.com/cookiecutter/cookiecutter)

Another cool thing about cookiecutter is that it works for any project structure, and there are quite a few already made templates in the pantry.

If you are interested in creating your own template [cookiecutter.readthedocs.io](https://cookiecutter.readthedocs.io/en/latest/). Templates use jinja2, but templates not in the scope of this series.

## Read The Docs
Read the docs provides documentation for your project. 


## Travis CI
Travis CI (Continuous integration)

## License

## Manifest

## Tests

## Docs

## Other optional files
- Contributors.md
- Authors.md
- Changelog.md