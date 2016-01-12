
# Foundation-Jekyll
The awesomeness of [Foundation][1] 6... powered by [Jekyll][2]

### Version
Current - 1.5.0

## About
Foundation-Jekyll is the quickest way to get started building static sites, prototypes, blogs, portfolios and much more. Foundation-Jekyll is flexible, yet highly customizable and ready to be deployed to Github Pages or your own hosting environment.

Foundation-Jekyll assumes the following:
- Minimum comfort level using the Terminal
- Development environment setup (Homebrew, Ruby, xCode, etc...)
- Some familiarity using Jekyll or are willing to get your hands dirty.
- Love using Foundation to build websites
- This project was created by @aaronkwhite in Colorful Colorado.

### Get Started
Install Jekyll

```
gem install jekyll
```

Clone the repo and start building your site:

```
 git clone git@github.com:aaronkwhite/foundation-jekyll.git foundation-jekyll
```

The core components are located in the *source* directory, so you can better organize your content and structure.

```
foundation-jekyll/
├── _site/
├── _source/
    ├── _data/
        ├── sample.json
    ├── _drafts/
        ├── 2014-12-14-draft-post.md
    ├── _includes/
        ├── header.html
        ├── footer.html
    ├── _layouts/
        ├── default.html
    ├── _posts/
        ├── 2014-12-14-post-one.md
        ├── 2014-12-14-post-two.md
    ├── assets/
        ├── fonts/
        ├── images/
        ├── javascripts/
            ├── vendor/
              ├── jquery/
            ├── ...
            ├── ...
            ├── foundation.min.js
            ├── ...
            ├── ...
            ├── motion-ui.js
            ├── scripts.js
        ├── stylesheets/
          ├── components
          ├── font-awesome/
          ├── forms/
          ├── grid/
          ├── typography/
          ├── util/
          ├── vendor/
          ├── _global.scss
          ├── _settings.scss
          ├── _theme.scss
          ├── _variables.scss
          ├── foundation.scss
          ├── style.scss
    ├── 404.html
    ├── index.html
    ├── feed.xml
├── _config.yml
├── .gitignore
├── LICENSE
├── README.md
```

We're using [Foundation][1] & Font-Awesome [Sass][3] Sass compiled by Jekyll automatically when we build the source.

The primary stylesheet '/assets/stylessheets/style.scss' file is configured to include all necessary files for Foundation, Font-Awesome and your custom styles, just add your custom styles to '/assets/stylesheets/_theme.scss'.

To test your site locally just run:

```
jekyll serve
```

*Note:* Make sure you update your git remote before you try to push any changes.

### Dependencies
 - ruby
 - Jekyll
 - kramdown
 - pygments

## Support/Contributing
If you run into any issues or bugs, please create an issue in Github. Unfortunately I can't help everyone via email or twitter, I'm only one person.

If you would like to contribute to this repo, hit me up on twitter [@aaronkwhite](http://twitter.com/aaronkwhite) and then we can talk pull requests.

## License

[MIT](http://opensource.org/licenses/MIT)




[1]: http://foundation.zurb.com
[2]: http://jekyllrb.com
[3]: http://sass-lang.com
[4]: http://compass-style.org
[5]: https://incident57.com/codekit
