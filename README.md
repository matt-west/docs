# Documentation Builder with Jekyll

[![Build Status](https://travis-ci.org/matt-west/docs.svg)](https://travis-ci.org/matt-west/docs)

A simple Jekyll boilerplate for creating a documentation site.

Created by [Matt West](http://mattwest.io) at [No Divide Studio](http://nodividestudio.com).


## Getting Started

Clone the repo and install the require gems.

```
git clone git@github.com:matt-west/docs.git
cd docs
bundle install
```


## Adding Collections

The site uses Jekylls collection feature to order pages. Refer to the documentation [here](http://jekyllrb.com/docs/collections/).


### Testing

Test that your rendered documentation files are up to scratch with [HTML::Proofer](https://github.com/gjtorikian/html-proofer).

```
rake test
```
