# Welcome to sample of RefineryCMS - I named it CoachingPlus

# Refinery CMS Blog [![Build Status](https://travis-ci.org/refinery/refinerycms-blog.svg?branch=master)](https://travis-ci.org/refinery/refinerycms-blog)

Simple blog engine for [Refinery CMS](http://refinerycms.com). It supports posts, categories and comments.

This version of `refinerycms-blog` supports Refinery 4.x and Rails 5.1.x (Ruby 2.2+). To use Rails 4.x / Refinery 3.1.x / Ruby 2.1 or older use the [refinerycms-blog "Refinery CMS 3-0 stable branch"](http://github.com/refinery/refinerycms-blog/tree/3-0-stable).

Options:

* Comment moderation
* [ShareThis.com](http://sharethis.com) support on posts. To enable, set your key in Refinery's settings area.

## Requirements

Refinery CMS version 4.0.0 or above (Ruby 2.2 or above).

## Install

Open up your ``Gemfile`` and at the bottom, add this line:


```ruby
gem 'refinerycms-blog', git: 'https://github.com/refinery/refinerycms-blog', branch: 'master'
```

Note: if the [refinerycms-page-images](https://github.com/refinery/refinerycms-page-images) extension is also installed, make sure `gem refinerycms-blog` comes before `gem 'refinerycms-page-images'`.

Now, run ``bundle install``

Next, to install the blog plugin run:

    rails generate refinery:blog

Run database migrations:

    rake db:migrate

Finally seed your database and you're done.

    rake db:seed# Refinery CMS Blog [![Build Status](https://travis-ci.org/refinery/refinerycms-blog.svg?branch=master)](https://travis-ci.org/refinery/refinerycms-blog)

Simple blog engine for [Refinery CMS](http://refinerycms.com). It supports posts, categories and comments.

This version of `refinerycms-blog` supports Refinery 4.x and Rails 5.1.x (Ruby 2.2+). To use Rails 4.x / Refinery 3.1.x / Ruby 2.1 or older use the [refinerycms-blog "Refinery CMS 3-0 stable branch"](http://github.com/refinery/refinerycms-blog/tree/3-0-stable).

Options:

* Comment moderation
* [ShareThis.com](http://sharethis.com) support on posts. To enable, set your key in Refinery's settings area.

## Requirements

Refinery CMS version 4.0.0 or above (Ruby 2.2 or above).

## Install

Open up your ``Gemfile`` and at the bottom, add this line:


```ruby
gem 'refinerycms-blog', git: 'https://github.com/refinery/refinerycms-blog', branch: 'master'
```

Note: if the [refinerycms-page-images](https://github.com/refinery/refinerycms-page-images) extension is also installed, make sure `gem refinerycms-blog` comes before `gem 'refinerycms-page-images'`.

Now, run ``bundle install``

Next, to install the blog plugin run:

    rails generate refinery:blog

Run database migrations:

    rake db:migrate

Finally seed your database and you're done.

    rake db:seed

