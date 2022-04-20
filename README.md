<!--- CARD BEGIN --->

![DNB-Hugo/HEAD](.github/github-card-dark.png#gh-dark-mode-only)
![DNB-Hugo/HEAD](.github/github-card-light.png#gh-light-mode-only)

<!--- CARD END --->

# David's Neighbour GoHugo Component / Pictures

Shortcodes I use in multiple themes for my Hugo websites.

### Installing

Step 0.5: enable modules in your own repository if not already done so.

```shell script
hugo mod init github.com/username/reponame
```

Step 1: add the module to your required modules in `config.toml`.

```toml
[module]

[[module.imports]]
path = "github.com/davidsneighbour/hugo-pictures"

```

The next time you run hugo it will download the latest version of the module.

This module adds a documentation on development environments under [http://localhost:1313/shortcodes/](http://localhost:1313/shortcodes/). If your local `hugo server` runs under a different host you can find the documentation of course under _that_ host.

### Updating

To update this module:

```shell script
hugo mod get -u github.com/davidsneighbour/hugo-pictures
```

To update all modules:

```shell script
hugo mod get -u
```

### Overriding shortcodes

To override shortcodes just add a file in your own shortcode directory with the name of the shortcode that you want to replace.

[Read more about theme components](https://gohugo.io/themes/theme-components/).

## Used By

This component is used by the following websites and tools:

- [kollitsch.de](https://kollitsch.de)
- [davids-neighbour.com](https://davids-neighbour.com)
