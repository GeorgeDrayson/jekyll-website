# Kit's personal website

Dependencies:

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