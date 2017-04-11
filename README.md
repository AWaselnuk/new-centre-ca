# newcentre.ca

This is a simple Jekyll site for the newcentre.ca project.

## Get started on Windows

If you are using Windows, you might not have Git installed. You should start by [installing Git](http://www.jamessturtevant.com/posts/5-Ways-to-install-git-on-Windows/) before moving on to the main setup below.

## Get started

1. [Install Ruby 2.3.3](https://www.ruby-lang.org/en/documentation/installation/). Be sure to follow the instructions most appropriate for your operating system.
1. Install Bundler. `gem install bundler`
1. Install Jekyll. `gem install jekyll`
1. Navigate to the project directory ([using the change directory command](http://www.digitalcitizen.life/command-prompt-how-use-basic-commands)) and type `jekyll serve` to build the site. You should see it in your web browser at http://localhost:4000/.

## More info

This website is built with [Jekyll](https://jekyllrb.com/) using the [Athena theme](https://github.com/broccolini/athena).

Read the [Jekyll docs](https://jekyllrb.com/) for more information on how to write blog posts.

Read the [Markdown cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) to learn how to format blog posts.

## Writing workflow

Here is a suggested workflow for writing a blog post.

1. Make sure your local Git repository is up to date. `git pull`
1. Copy the template file in the `_drafts` folder. Change the name of the file and the front matter to reflect the current date and whatever the article will be called.
1. Choose a category. I think we should just have two for now: `articles` and `conference`.
1. Run `jekyll serve --drafts` to preview your work in a web browser.
1. When you are finished writing the article, commit your changes to git by saving the file and then typing. `git add . && git commit -am 'Your message here'`.
   * An example of a good message is `'Added draft for post about terminology'`. Keep it short, relevant to the work you did, and in the past tense.
1. Update the remote Git repository with `git push origin master`.

## Publishing a post

When you are ready to publish a post, you simply have to move the post to the `_posts` folder and update the Git repository.

1. Move the post from `_drafts` to `_posts`.
1. Update Git with `git add . && git commit -am 'Moved post to posts folder'`
1. Update the remote GIt repository with `git push origin master`.
1. The post should be live in under a minute.

## Peer reviewed articles

Using Github, we can leverage sophisticated tools for reviewing articles or website content as a team. Once we get more comfortable with the basic publishing workflow, we can write up docs for how to do reviews on Github.
