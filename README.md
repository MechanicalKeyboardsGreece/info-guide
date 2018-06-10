# [Mechanical Keyboards Greece Info Guide](https://mechanicalkeyboardsgreece.github.io/info-guide/)

## Goal
The purpose of this project is to create an "Information Guide" webpage for the "Mechanical Keyboards Greece" community.

## Contributing
Contributions are more than welcome, however opening an [issue](https://github.com/MechanicalKeyboardsGreece/info-guide/issues?q=is%3Aissue+is%3Aopen+sort%3Aupdated-desc) (or getting assigned an existing one) is recommended to discuss overall direction and avoid two people working on the same part.

### Building site
After `git clone`-ing the project (and assuming Ruby's `Gem` is installed) in your system, you need to run:
```bash
gem install bundler
```

Then you need to install the required dependencies:
```bash
bundle install
```

Finally, you can build and run the site locally @ `http://127.0.0.1:4000/info-guide/` so as to work on and review changes before commiting.
```bash
bundle exec jekyll serve
```
*NOTE:* Running the above may take ~5 mins to setup Jekyll, but afterwards changes should be applied within a few seconds, after which they should be visible by refreshing the local page in your browser.