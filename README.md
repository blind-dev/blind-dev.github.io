# blinddev.org

This is the source for the [blinddev.org](https://blinddev.org) website.

## Goals

These are still very much up int he air, but initially some of the goals for
this website include:

 * A directory of projects relating to software development and accessibility.
 * A directory of developers interested in working on projects relating to
   software development and accessibility.
 * A news source for updates relating to such projects.
 * A resource including reviews, tutorials, guides and related materials
   relating to accessibility and software development tools.

But this is very much meant to be a collaborative effort. So if you have other
ideas for this website don't hesitate to tell us about them.

## Contributing

Currently this website is using the static site generator [Jekyll](https://github.com/jekyll/jekyll). Most of the content is generated from markdown files
and for the most part the learning curve is relatively low. This repository is
using GitHub Pages, so every commit to `master` will update blinddev.org
automatically. As such, please submit any proposed changes as a pull request.

### OSX Setup

Here are the steps to get started with OSX:

 1. Install ruby, `brew install ruby`
 2. Install the bundler gem, `gem install bundler`
 3. Clone this repo, `git clone git@github.com:blind-dev/blind-dev.github.io.git`
 4. Enter the repo's root directory, `cd blind-dev.github.io`
 5. Install the dependencies by running `bundle`
 6. Run Jekyll locally, `bundle exec jekyll serve`
 7. Visit [http://localhost:4000](http://localhost:4000) to see it running
    locally

From here, check out the [Jekyll Documentation](https://jekyllrb.com/docs/home/).

### Linux & Windows Setup

Please contribute instructions if you're a Linux or Windows user.
