# Saraswati.js.org
![](./saraswati.jpg)

The website.

`Saraswati.js` powered. Gatsby backed. 

Eat your own dogfood and all that right?

## How it is all put together
### `saraswati-site`
All the documentation all features used and examples.

### `alexandria`
The main repository. Everything here should be considered "core" and will be used in the gatsby plugins. Theoretically we should be able to use any static site generator (or even build our own) and use all the code code in here w/o issue.

### `bontemps`
Server stuff.

### `alexandria-tools`
CLI stuff.

### `alexandria-remark-plugins`
Custom `remark` plugins will be housed here for use elsewhere.

### `alexandria-gatsby-plugins`
`Gatsby` specific plugins. Some are forks others are custom.

### `alexandria-design`
CSS, components et al. This is to keep everything as seperated as possible (easier to push changes).

All `React`, sorry.

### `alexandria-rfcs`
Make a pull request and add an RFC here for the future. (and a PR for existing functionality)

## TODO
lol, like, everything yo.

* Rename all `alexandria` to `saraswati`
* A CNAME as well so I can actually use the `Saraswati.js.org` website under that domain.