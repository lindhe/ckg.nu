# ckg.nu
Investigating to move ckg.nu from Wordpress to GitHub Pages

# Development

I'm not very familiar with Jekyll, so these instructions can probably be improved a lot.

## Prerequisites

* jekyll
* yamllint

## Building

```shell
jekyll build
firefox ./_site/index.html
```

## Linting

```shell
yamllint ./_config.yml
```

