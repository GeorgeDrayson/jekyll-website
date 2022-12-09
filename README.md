# Kit's personal website

Dependencies:

- Ruby
- RubyGems
- Jekyll

## Setup
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

Run the website locally:
```
bundle exec jekyll serve
```