# Setting up Jekyll

## Install Jekyll and Bundler gems through RubyGems

```
gem install jekyll bundler
```

**Troubleshooting**

* I had to upgrade my Ruby version and [this Stackoverflow answer](https://stackoverflow.com/a/38194139) was very helpful.

# Bootstrap a blog

## Create a new Jekyll site at ./myblog

```
jekyll new myblog
```

## Change into your new directory

```
cd myblog
``` 

## Build the site on the preview server

```
bundle exec jekyll serve
```

* Now browse to http://localhost:4000

# Basic usage
