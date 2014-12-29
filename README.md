
# Foundation-Jekyll
A bare bones [Foundation][1] & [Jekyll][2] boilerplate to get up and running fast.

### Version
Current - 1.1.0

## About
This boilerplate was created as a starting point to use [Foundation][1] & [Jekyll][2] to create static websites. There aren't many (if any) [Foundation][1] & [Jekyll][2] boilerplates, so I created one. The structure is geared more towards building static sites and prototypes, not just blogs. Hopefully you'll find it as useful as I do.


### Get Started
Clone the repo and start building your site:

```
 git clone git@github.com:aaronkwhite/foundation-jekyll.git project-name
```

The core components are located in the *source* directory, so you can better organize your content and stucture.

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
    ├── _scss/
    ├── assets/
        ├── fonts/
        ├── images/
        ├── javascripts/
            ├── foundation/
            ├── foundation.min.js
            ├── jquery-2.1.1.min.js
            ├── modernizr-2.8.3-min.js
            ├── scripts.js
        ├── stylesheets/
          ├── style.scss
    ├── 404.html
    ├── index.html
    ├── feed.xml
├── .gitignore
├── LICENSE
├── README.md
├── _config.yml
```

We're using [Foundation][1] & Font-Awesome [Sass][3] compiled by Jekyll automatically when we build the source. All Sass files are located in the '_scss/' directory including the customized skin.

The primary stylesheet '/assets/stylessheets/style.scss' file is configured to include all necessary files for Foundation, Font-Awesome and your custom styles.

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


## Hosting on Github
If you plan on hosting your site or blog on Github Pages, you will need to move all the files in the 'source' directory to the root of your project. This is due to the Github Pages build system overriding the source flag in _config.yml.

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
