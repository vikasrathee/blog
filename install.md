# Ubuntu 16.04
```
$ sudo apt-get update
$ sudo apt-get install ruby ruby-dev make gcc
$ sudo gem install jekyll bundler
```

# Ubuntu 14.04
```
$ sudo apt-get update
$ sudo apt-get install ruby2.0 ruby2.0-dev
$ sudo gem install bundler
$ sudo gem2.0 install jekyll bundler
```

## How to Start Jekyll
```
$ jekyll new myblog
$ cd myblog
$ bundle exec jekyll serve

# or simply $ jekyll serve
# with reload and refresh every file changes $ jekyll serve -w
# => Now browse to http://localhost:4000
```
