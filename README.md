---
layout: page
permalink: /readme/
---

# README

## Purpose

The purpose of this README is to demonstrate how you can host and format your own resume using Markdown, StackEdit, Github Pages and Jekyll. This demonstration will be performed by relating what we have learned from Andrew Etter's book *Modern Technical Writing*.

## Prerequisites

* Resume formatted in Markdown
  * (Optional) Markdown Editor ([local](https://typora.io/) or [web-based](https://stackedit.io))
  * For your resume, make sure you only include information that is necessary for your prospective employers to know. You should be including any relevant work experience and education, you need not include your personal information other than your name and contact information.[^1]
* [GitHub account](https://github.com/)
* [Ruby](https://www.ruby-lang.org/en/downloads/)
* [RubyGems](https://rubygems.org/pages/download)
* [GCC](https://gcc.gnu.org/install/)
* [Jekyll](https://jekyllrb.com/docs/installation/windows/)

## Instructions

### Step 1: Acquire the prerequisites

1. Install the prerequisites listed above

Markdown is a popular markup language used by web editors to produce content easily online. It is more lightweight compared to other markup languages such as XML, meaning it is much more readable and user-friendly.[^2]<br> 
Jekyll is a static website generator that allows its users to create and host their own websites. Static websites are perfect to use for hosting a site as simple as a resume. It allows for the usage of pages from Markdown files that can be added and edited whenever needed.[^3] As your resume should be a single page (or many, to your choosing), Jekyll provides a simple and easy to use resource to host your website. If any new experience is needed to be added to your resume, simply add it to your respective Markdown file and commit to your respository. 
GitHub allows users to share and collaborate on distributed projects. GitHub also allows for version control which allows users to view change logs and previous versions of the project. This can be useful for reviewing when an error may have occurred and what stage to revert to to rectify the issue.[^4]

### Step 2: Create a new repository on GitHub

1. Create a new public repository
2. Name the repository as `[your-github-username].github.io`
    * This will be the link you will use to later access your website.

### Step 3: Create your Jekyll site

1. Create a Jekyll site `resume`
    * In the terminal, enter `jekyll new resume`.
2. Change into your new `resume` directory
    *  In the terminal, enter `cd resume`.
3. Add `gem "webrick"` on a new line in the Gemfile
4. Build the site locally
    * In the terminal, enter `bundle exec jekyll serve`.
5. Access your website locally
    * In your web browser, visit `http://localhost:4000`.

You will now be seeing the default Jekyll website.

### Step 4: Upload your resume to your website

![Step 4](step4.gif)
*Showcasing substeps 2 through 4*

1. Rename your Markdown-formatted resume to `index.markdown`
    * This will display your resume as the homepage to your website.
2. Add a header to your Markdown-formatted resume
3. Add `layout: home` to your header
4. Add `title: [your-title]` to your header
5. Remove the `about.markdown` file from the repository
6. Remove the plugins from the `_configs.yml` file in the repository

### Step 5: Host your website using GitHub Pages

1. Open your repository settings
2. Navigate to `Pages` on the sidebar under `Code and automation`
3. Select `Deploy from branch` for source
4. Select the branch you would like to deploy from
5. Save your settings
6. Visit `[your-github-username].github.io`

Your website should now be hosted.

### Step 6: Create a README

As I hope you found this README helpful, I hope you also create your own for the purposes of aiding others in how to create and host their own resumes. If you made it this far, you should now know everything needed to explain to others how to host their resume online.[^1] Your README should contain a summary of your work and instructions similar to the ones you followed.[^5] 

### Step 7: Customize

There are plenty of available themes to choose from for Jekyll. Check [More Resources](#more-resources) below for a range of resume Jekyll themes. Maintain the readability of your resume when choosing a theme. It is important that your resume remains intriguing and distinguishable to your prospectiove employers.[^1] 

## More Resources

* [GitHub Flavoured Markdown Tutorial](https://github.github.com/gfm/)
* [Andrew Etter's *Modern Technical Writing*](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)
* [Jekyll Resume Themes](https://jekyllthemes.dev/tag/resume/)

## Authors & Acknowledgements

Authored by Taylor Roy. <br>
Concepts related from Andrew Etter's *Modern Technical Writing*<br>
Peer reviewed by Vedant Pulahru, Josh Sigurdson & Mansimar Bhasin.

## FAQs

1. Why is Markdown better than a word processor?
    * Markdown is better than a wood processor as it allows the user a lot more freedom for formatting, and later for publishing. Markdown and all its flavours allow web writers to produce static web content much easier without having to write in the less readable HTML. 

2. Why is my resume not showing up?
    * If you are able to run your website through Jekyll and your resume is not showing up, there may be a few potential solutions. Firstly, make sure your resume is Markdown-formatted and not a text file. Next, check and see if your resume Markdown file is located in your Jekyll repository. This will be the same folder/directory containing your Gemfile. If it still is not showing up, try adding "layout: page" to your Markdown header within your resume file. If still you are encountering issues, revert back to [Step 4](#step-4-upload-your-resume-to-your-website).

[^1]: Andrew Etter's *Modern Technical Writing*., p. 80
[^2]: Andrew Etter's *Modern Technical Writing*., p. 33
[^3]: Andrew Etter's *Modern Technical Writing*., p. 50
[^4]: Andrew Etter's *Modern Technical Writing*., p. 75
[^5]: Andrew Etter's *Modern Technical Writing*., p. 47
