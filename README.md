# README

## Purpose

The purpose of this README is to demonstrate how you can host and format your own resume using Markdown, StackEdit, Github Pages and Jekyll. This demonstration will be performed by relating what we have learned from Andrew Etter's book *Modern Technical Writing*.

## Prerequisites

* Resume formatted in Markdown
  * Markdown Editor ([local](https://typora.io/) or [web-based](https://stackedit.io))
* [GitHub account](https://github.com/)
* [GitHub CLI](https://cli.github.com/) (optional, will be used for this demonstration)
...
* Jekyll

## Instructions

### Step 1: Acquire the prerequisites listed above

The links above will direct you to where to download & obtain the prerequisites and how to install them.

### Step 2: Create a new repository on GitHub with GitHub Pages

1. Create a new repository and name it as `[your-github-name].github.io`

Follow this [tutorial](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site) on how to create a GitHub Pages repository to host your site.

(everything else that comes with this as well)

add gem "webrick" to Gemfile

### More Resources

* [GitHub Flavoured Markdown Tutorial](https://github.github.com/gfm/)
* [Andrew Etter's *Modern Technical Writing*](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)
* ...

## Authors & Acknowledgements

Authored by Taylor Roy. <br>
Edited by Vedant Pulahru, Josh Sigurdson & Mansomar Singh. <br>
Jekyll Theme created by ...

## FAQs

1. Why is Markdown better than a word processor?
* Markdown is better than a wood processor as it allows the user a lot more freedom for formatting, and later for publishing. Markdown and all its flavours allow web writers to produce static web content much easier without having to write in the less readable HTML. 

2. Why is my resume not showing up?
* If you are able to run your website through Jekyll and your resume is not showing up, there may be a few potential solutions. Firstly, check and see if your resume Markdown file is located in your Jekyll repository. This will be the same folder/directory containing your Gemfile. If it still is not showing up, try adding "layout: page" to your Markdown header within your resume file. 

