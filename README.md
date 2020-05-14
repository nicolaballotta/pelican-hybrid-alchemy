# Pelican Hybrid Alchemy theme
> My custom theme for [hybridhacker.com](https://hybridhacker.com).

This theme is based on [pelican-alchemy](https://github.com/nairobilug/pelican-alchemy), a very nice and clean theme for [Pelican](http://getpelican.com) static site generator.

## Installation

### From Git repo

Clone the repo:

```bash
git clone https://github.com/nicolaballotta/pelican-hybrid-alchemy
```

Set the `THEME` variable in your Pelican config:

```python
THEME = '<PATH_TO_REPO>'
```

### As a Submodule

In your Pelican site:

```bash
mkdir themes
git submodule add https://github.com/nicolaballotta/pelican-hybrid-alchemy themes/pelican-hybrid-alchemy
```

And in Pelican config:

```python
THEME = 'themes/pelican-hybrid-alchemy'
```
