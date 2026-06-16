# Thelia recipes

Symfony Flex recipes for Thelia packages. When you install a Thelia package that has a recipe here, Flex applies it: it registers the bundle, writes default configuration, copies files and sets environment variables.

The Thelia skeleton (`thelia/thelia-skeleton`) declares this endpoint under `extra.symfony.endpoint`, so projects created from it pick the recipes up automatically.

## Layout

- `index.json` lists the packages that have a recipe, with their versions.
- `<vendor>.<package>.<version>.json` is a recipe: the bundle to register, the files to copy and the environment variables to set.
- `archived/` keeps older Symfony recipe versions kept as dependencies.

See the [Symfony Flex recipe format](https://github.com/symfony/recipes) for the file structure.
