# brume

forked from aigarsdz/brume

## Usage

Brume can be installed just like any other Jekyll theme as described [here](https://jekyllrb.com/docs/themes/#installing-a-theme),
but there are a couple of additional steps you have to take.

1. All the links are defined in a file *_data/links.yml*, therefore you'll have to create a *_data*
directory and put this file there in order for navigation to be displayed.
2. Brume uses `home` layout for the home page (like the default Jekyll theme). All you need to do
is create an *index.html* or *index.md* file with `layout: home`. If you want the home page to be
listed in the navigation you have to add `title` to it's front matter that matches
the title you used for the home page link in the *links.yml* file. Titles are used to indicate
the current page.

## Theme customization

This theme has 4 predefined colors that can be used for links:

- azul
- ruby
- amber
- avocado

By default it uses *avocado*, but if you want to select another one just change the `color_scheme` setting in
*_config.yml* file.

Express your thoughts about brume on Twitter [@aigarsdz](http://twitter.com/aigarsdz), and help me make it better!
