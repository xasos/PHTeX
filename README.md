# PHTeX
Posthaven theme based on the [Modern theme](https://github.com/posthaven/modern-theme), styled to look like LaTeX. Inspired by [Colah's blog](http://colah.github.io/).

## Screenshot

![Screenshot](/assets/screenshot.png?raw=true)

## Theme Building Resources

* [Posthaven theme documentation](http://theme-docs.posthaven.com/)
* See the [posthaven_theme](https://github.com/posthaven/posthaven_theme) gem for theme file upload via the API.

## Building Stylesheets

### Install Gems

Install [bundler](http://bundler.io):

```
gem install bundler
```

Install the gems:

```
bundle install
```

### Building SCSS

Build `assets/blog.css`:

```
rake compile
```

Watch `src/blog.scss` and build on update:

```
rake watch
```

## Deploying to Posthaven
Instructions can also be found [here](https://theme-docs.posthaven.com/). Grab an API key [here](https://posthaven.com/account/theme_api_key).
```
gem install posthaven_theme
git clone https://github.com/xasos/PHTeX.git
cd PHTeX
phtheme configure YOUR_API_KEY
phtheme upload
```

## License
[MIT License](LICENSE)
