# Kit's personal website

### Dependencies:

- Ruby
- RubyGems
- Jekyll

## Local setup
Make sure you have installed the required dependencies, then run:
```
bundle
```
```
bundle update
```
If you get the error:

cannot load such file -- webrick (LoadError)

Run:
```
bundle add webrick
```
## Run a local server

To run the website on localhost use this command:
```
bundle exec jekyll serve
```
## Customising the website

### Change bio photo
Replace the file ./assets/images/bio-photo.jpg with a square bio photo with the same file name

### Change bio
Replace the bio on line 63 of _config.yml

### Add website description for Google
Replace the description on line 18

### Add text to the about page
Navigate to the file ./pages/about.md
Replace the text starting with 'Tempor velit sint sunt...'

# How to add posts
Posts are contained in the _posts folder
Here you will find some example posts that the minimal mistakes github page made to show you the features
Basically these are markdown files just like a README. I would check out this [link](https://www.markdownguide.org/cheat-sheet/) to understand how to use markdown if you haven't before.

!!!Very important!!!
Post filenames must follow the convention yyyy-mm-dd-title
Title should be in lowercase with spaces separated by dashes
The file should be of the type .md

Within the file follow the convention of the example posts ie:
```
---
title: "Post: Your Title Here"
last_modified_at: [date in this form 2016-03-09T16:20:02-05:00]
categories:
  - Blog
tags:
  - tag 1
  - tag 2
  - etc.
---

Your blog using markdown format
```