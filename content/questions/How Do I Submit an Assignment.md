---
title: "How Do I Submit an Assignment?"
date: 2020-01-13T20:39:19-06:00
draft: false
---

Submitting an assignment requires several steps. Here's a detailed walkthrough.

1. Commit your code via git.
2. Push your code up to Github.
3. Publish your code via Github Pages.
4. Submit your Github URL to Canvas.
5. Double-check your URL after submitting.

## 1. Commit Your Code

The Github Desktop application will detect changed files and will prompt you to commit your changes. Keep in mind that "committing" just means that we're done for now and want git to keep track of what we've changed.

![Changes detected in Github Desktop](https://raw.githubusercontent.com/britton-clapp/cse204faq-html/master/img/github-desktop-changes.png)

Make sure that you explain what you did in the box that says "Update index.html", and then press "Commit to master". Once you've pressed that button, your changes are recorded in your local git repository.

## 2. Push to Github

To publish your files, first you have to make sure that the newest versions have been sent to Github.com. When working with a git repo, this is called a "push".

![Changes detected in Github Desktop](https://raw.githubusercontent.com/britton-clapp/cse204faq-html/master/img/github-desktop-local-commit-waiting.png)

Press the blue button that says "Push origin" to send your files to your account on Github.com. Once you've done that, anything tracked by your local git repository will also be saved on Github.com.

## 3. Publish with Github Pages
Find your repository page on Github.com. Github Desktop has a button labeled "View on Github" that will take you directly to it.

Click the "Settings" tab.

![Github repository settings](https://raw.githubusercontent.com/britton-clapp/cse204faq-html/master/img/github-repo-settings.png)

Scroll down almost to the bottom of the settings page, and you'll find the Github Pages section.

![Github pages settings](https://raw.githubusercontent.com/britton-clapp/cse204faq-html/master/img/github-pages.png)

Change the dropdown from "None" to "master branch". This will take all the files in your `master` branch and automatically publish them.

You only have to do this once for each repository, and once you've done it, new changes will automatically be published.

