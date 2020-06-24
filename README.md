# Showcase theme for Hugo

![Latest Release](https://img.shields.io/github/tag/apvarun/showcase-hugo-theme.svg)
![Showcase hugo theme](https://img.shields.io/github/license/apvarun/showcase-hugo-theme)
![Hugo generator](https://img.shields.io/badge/generator-hugo-brightgreen)

Showcase is a minimal, single page theme for Hugo

![Preview](https://github.com/apvarun/showcase-hugo-theme/blob/master/images/screenshot.png)

Features:

- Auto-generated menu
- Responsive content
- Filtering content
- Social links
- Custom menu

## Get the theme

Run from the root of your Hugo site:

```sh
git clone https://github.com/apvarun/showcase-hugo-theme.git themes/showcase
```

Alternatively, you can include this repository as a [git submodule](https://git-scm.com/docs/gitsubmodules). This makes it easier to update this theme if you have your Hugo site in git as well:

```sh
git submodule add https://github.com/apvarun/showcase-hugo-theme.git themes/showcase
```

## Preview the theme

Showcase theme ships with an fully configured example site. For a quick preview:

```sh
cd themes/showcase/exampleSite/
hugo serve --themesDir ../..
```

Then visit `http://localhost:1313/` in your browser to view the example site.

## Add content

The following explains how to add content to your Hugo site. You can find sample content in the `exampleSite/` folder.

### Structure:
    .
    ├── ...
    ├── projects       # Section Name
    │   ├── project1   # Project 1
    │   ├── project2   # Project 2
    │   └── _index     # (optional) Customize section name &
    │                  # default image for section contents
    └── ...


## Configure your site

From `exampleSite/`, copy `config.toml` to the root folder of your Hugo site and change the fields as you like. Helpful comments are provided.

## Menu

Menu in Showcase theme is auto-generated from the sections inside your content folder.

You can also add a custom menu item using the `config.toml` and disable auto-generated sections if not required. Refer config in [exampleSite](https://github.com/apvarun/showcase-hugo-theme/blob/master/exampleSite/config.toml)

## Google Analytics

Set `googleAnalytics` in `config.toml` to activate Hugo's [internal Google Analytics template](https://gohugo.io/templates/internal/#google-analytics).

## Used By

- [Madhu Akula](https://madhuakula.com/content/)
- [@cloudmiracle](http://cloud.vn/)

## Issues

If you have a question, please [open an issue](https://github.com/apvarun/showcase-hugo-theme/issues) for help and to help those who come after you. The more information you can provide, the better!

## Contributing

Contributions are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

Licensed under [MIT](LICENSE)

## Acknowledgements

[Madhu Akula](https://github.com/madhuakula)
