# Overview

[Octopress](http://octopress.org/) Theme for [k.ernel.org](http://k.ernel.org/)

# Install

```sh
cd octopress/.theme
git clone git://github.com/g1u770ny/object-octopress-theme.git object
cd ..
rake install["object"]
```

The sidebar of the theme has three columns by default. The section element of three asides should have "first odd", "even", "odd" class attribute. Reference to the three asides used by this theme:  [recent_posts.html](https://github.com/g1u770ny/object-octopress-theme/blob/master/source/_includes/asides/recent_posts.html), [twitter.html](https://github.com/g1u770ny/object-octopress-theme/blob/master/source/_includes/asides/twitter.html), [delicious.html](https://github.com/g1u770ny/object-octopress-theme/blob/master/source/_includes/asides/delicious.html).
Do not forget to modify the _config.yml file to include these asides:

```yaml
default_asides: [asides/recent_posts.html, asides/twitter.html, asides/delicious.html]
```