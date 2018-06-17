# Website for NGPS 2019 @ SAC

## How to contribute

Track organizers will be enabled as admins.
If you are an organizers but are not yet administrator, contact Danilo Pianini.

### Editing existing pages

Base pages, with the same structure of other workshops of previous years, are in the `_posts` folder.
It's all plain markdown.

### Adding new pages

1. Create a new page in `_posts`, by copy/pasting/renaming an existing one
2. Carefully choose the date: the newer the page, the higher will be displayed in the home page
3. Add an entry in the navigation menu by editing `_data/navigation.yml`
4. If you want to be stilish, find a nice image of the venue on Flicker (please make sure the license is Creative Commons BY-NC-SA or more permissive), add it to `assets/images/`, and refer it for insertion in the header

### Committing changes

Committing a change on the branch `master` and pushing will trigger a site regeneration by GitHub Pages

### Testing the website locally

The website is developed with [Jekyll](https://jekyllrb.com/). To use it locally:

1. Install Ruby Gem. This depends on your operating system. Once done, you will have the `gem` command available on the command line
2. Clone the website in a folder of your like, say `tracksite`
3. Open a terminal inside `tracksite`
4. Issue `gem install jekyll bundler`
5. Issue `bundle exec jekyll serve`
6. The website will get generated, a local http server will get spawn, and a link to a localhost port serving it will be displayed on the terminal.

