# Course slides for 'Falling in Love with Git' GDI Minneapolis Course

* Slides are at [https://gdiminneapolis.github.io/falling-in-love-with-git](https://gdiminneapolis.github.io/falling-in-love-with-git)
* Git Documentation: [https://git-scm.com/docs](https://git-scm.com/docs)
* GitHub Help: [https://help.github.com/](https://help.github.com/)

## Git Cheat Sheets

These can be found all over, we've included three:

* [GitLab Git Cheat Sheet](gitlab-git-cheat-sheet.pdf)
* [GitHub Git Cheat Sheet](github-git-cheat-sheet.pdf)
* [Atlassian Git Cheat Sheet](atlassian_git_cheatsheet.pdf)

## Resources

Some more resources for learning Git:

* [Learn Git Branching](http://learngitbranching.js.org/)
* [workspace  Git Cheatsheet](http://www.ndpsoftware.com/git-cheatsheet.html#loc=workspace;)
* [Git commands and shortcuts  ShortcutFoo](https://www.shortcutfoo.com/app/dojos/git)


## Contributing

We are always looking for help in improving our training materials. We'd like your participation as well!

First, read the [Contributor Covenant](CONTRIBUTOR_COVENANT.md).

Next, you can contribute in the following ways:

* Submit an problem, suggestion, or question via [Issues](https://github.com/gdiminneapolis/falling-in-love-with-git/issues)
* Write or update a page explaining something on the project [Wiki](https://github.com/gdiminneapolis/falling-in-love-with-git/wiki)
* Fork and clone the repo, cut a branch, make your changes, and submit a [Pull Request](https://github.com/gdiminneapolis/falling-in-love-with-git/pulls)

### Prerequisites

* Install [Jekyll](https://jekyllrb.com) (which requires [Ruby](http://ruby-lang.org))

### Downloading Slides

    $ git clone git@github.com:gdiminneapolis/falling-in-love-with-git.git
    $ cd falling-in-love-with-git

### Viewing slides while editing

    $ make

This will run Jekyll in server mode, hosting output on `http://localhost:4000` -- the URL will also be displayed in Jekyll's output.

Launch your browser at that URL and you can refresh the view every time you make a change.

### Publishing to Github Pages

    $ make publish

This will create the `publish/` directory and initialize it as a `git` repo pointing at the `gh-pages` branch of the repository, and run Jekyll in build mode. (Apologies, this isn't quite foolproof yet.)

The file `_publish.yml` in the root directory can be set to provide overrides and fill-ins needed for publishing on GH pages. Generally speaking, nothing needs to be done with these settings.

## Contributors

* [Amy Gelbart](https://twitter.com/amlyhamm) (Original author/creator)
* [Tamara Tmeple](https://github.com/tamouse)
* Add your name here! (See above.)
