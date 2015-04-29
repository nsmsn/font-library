Font Library
-----------

## Contributing

The are nearly 700 [Google Fonts](http://www.google.com/fonts), let's organize them!

### Background

Font Library is built with Jekyll and AngularJS, but you don't need to know either to add or edit the tags. To add or edit tags, you only need to know how to edit a file.

Each font family is stored as an object in `families.json`. Each family has an array of tags. The first tag is from Google's classification of the font. A few font's have the tag `greek` or `khmer` this is to denote the subset of this font, please do not delete these tags. Some families have additional keys such as `weight` or `italic`, that's because this font does not have a `regular` weight and these keys provide flags to output the family correctly.

Changes are welcome to editing the current tags and adding new ones.

### Adding/editing `families.json` guidelines

* Use double quotes `"`
* Do not delete or change the first tag (this is the classification defined by Google)
* Do not delete or change the `greek` or `khmer` tag, these denote the subset of the font.
* Keep the list alphabetical by family name
* The family name must match Google's exactly
* Tags should be lowercase

### Help wanted

You're welcome to start editing the `families.json` file to add or edit tags.

Want to help, but don't know where to start? Open your browser's Console:

![image](https://cloud.githubusercontent.com/assets/2180540/7383722/5d37c0b6-edf2-11e4-8b51-d271c7529385.png)

* **Help wanted! These fonts need to be added to families.json** &mdash; if Google adds a new font, but we haven't added it to `families.json` yet, then the Console will log it along with the exact entry you can copy and paste into `families.json`. Feel free to add additional tags to the entry.
* **Help wanted! These fonts need more tags in families.json** &mdash; if a family has less than 2 tags, then the Console will log it. Open the provided link to the specimen page and read the description to get ideas for tags. Try to use tags that are already established, but create new tags when necessary.

Please **create a pull request** or **create an issue** to add/edit tags or to add new Google fonts. If you're new to Github, I'm happy to walk you through it. I recommend reading [Creating an issue](https://help.github.com/articles/creating-an-issue/) and [Creating a pull request](https://help.github.com/articles/creating-a-pull-request/). If you need help with your pull request, create an issue and tag me in it `@katydecorah` and I'll help..
