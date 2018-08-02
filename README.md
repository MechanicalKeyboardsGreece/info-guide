# [Mechanical Keyboards Greece Info Guide](https://mechanicalkeyboardsgreece.github.io/info-guide/)

## Goal

The purpose of this project is to create and maintain an "Information Guide" webpage for the "Mechanical Keyboards Greece" community.

## Contributing

Help is more than welcome, however opening an [issue](https://github.com/MechanicalKeyboardsGreece/info-guide/issues?q=is%3Aissue+is%3Aopen+sort%3Aupdated-desc) (or getting assigned an existing one) is recommended to discuss overall direction and avoid two people working on the same part.  
Contributions and PRs should be done on the `master` branch, which will be later merged to `gh-pages`, from which the [Jekyll](https://jekyllrb.com/docs/home/) site is built by GitHub.

### Building site changes locally

After `git clone`-ing the project (and assuming Ruby's [Gem](https://rubygems.org/pages/download) is installed) in your system, you need to run:

```bash
gem install bundler
```

Then, you need to install the required dependencies:

```bash
bundle install
```

Finally, you can build and run the site locally @ `http://127.0.0.1:4000/info-guide/` so as to work on and review changes before commiting.

```bash
bundle exec jekyll serve
```

_NOTE:_ Running the above may take ~5 mins to setup Jekyll, but afterwards changes should be applied within a few seconds, after which they should be visible by refreshing the local page in your browser.

### Local changes preview

An easier alternative to local building, which is useful for quick and easy changes, is to use a "Markdown Preview" extension for your editor of choice. Examples:

- [Sublime Text plugin](https://packagecontrol.io/packages/MarkdownLivePreview)
- [Atom plugin](https://github.com/atom/markdown-preview)
- VS Code has this by default, but has extra features in various plugins

_CAUTION:_ This approach will not reflect the site's form under the Jekyll theme that is eventually used in building it, so inconsistencies are to be expected.