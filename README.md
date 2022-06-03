---
description: >-
  Welcome to Jekyll’s step-by-step tutorial. This tutorial takes you from having
  some front-end web development experience to building your first Jekyll site
  from scratch ..
---

# 1. Set Up

### Introduction

Welcome to Jekyll’s step-by-step tutorial. This tutorial takes you from having some front-end web development experience to building your first Jekyll site from scratch without relying on the default gem-based theme.

### Installation

Jekyll is a Ruby gem. First, install Ruby on your machine. Go to [Installation](https://jekyllrb.com/docs/installation/) and follow the instructions for your operating system.

With Ruby installed, install Jekyll from the terminal:

{% tabs %}
{% tab title="Linux" %}
```shell-session
craigsims@cloudshell:~/$ gem install jekyll bundler
```
{% endtab %}

{% tab title="Windows" %}
```shell
C:\Users\craigsims\dev> gem install jekyll bundler
```
{% endtab %}
{% endtabs %}

> **Optional:**
>
> Create a folder called `jekyll` and `cd` into it
>
> ```shell-session
> craigsims@cloudshell:~/$ mkdir jekyll
> craigsims@cloudshell:~/$ cd jekyll
> craigsims@cloudshell:~/jekyll$ 
> ```

Create a new `Gemfile` to list your project's dependencies:

{% tabs %}
{% tab title="Linux" %}
```shell-session
craigsims@cloudshell:~/jekyll$ bundle init
```
{% endtab %}

{% tab title="Windows" %}
```bash
C:\Users\craigsims\dev\jekyll> bundle init
```
{% endtab %}
{% endtabs %}

Edit the `Gemfile` in a text editor and add jekyll as a dependency:

```ruby
# frozen_string_literal: true

source "https://rubygems.org"

# gem "rails"
gem "jekyll"
```

Run `bundle` to install jekyll for your project.

{% tabs %}
{% tab title="Linux" %}
```
craigsims@cloudshell:~/jekyll$ bundle init
```
{% endtab %}

{% tab title="Windows" %}

{% endtab %}
{% endtabs %}

You can now&#x20;

