---
layout: post
author: Breaker
---

![Foto](https://i.pinimg.com/236x/93/92/21/93922166f205df82a7e93606ac189376.jpg)  ❧ CoBreak is a project of cracking hash ☙

## Description

software made in ruby with extensions
native in C ++, it is a fairly easy to use project, it consists of a SQLite database where it stores its data (eye) the default database is disabled, execute [cbrdb start] to start the database, others of The components of cobreak is that it works with parallelism with processes, so to save time when cracking a hash, to decorate it, cobreak has modules to create a specific type of hash, for example an MD5, however, you can also cipher and decipher a clear text

> (Warning) the default database is disabled

### installation
#### Gemfile:
{% highlight ruby %}
source "https://rubygems.org"

gem "cobreak"
{% endhighlight %}

##### and execute:
{% highlight bash %}
  $ bundle
{% endhighlight %}

##### or
{% highlight bash %}
  $ bundle install
{% endhighlight %}

##### or execute in terminal
```sh
  $ gem install "cobreak"
```

### Usage:

![Foto](assets/2021-09-05_03-05.png)

```bash
cobreak --bruteforce=md5 --wordlist=[WORDLIST] --input "d186321c1a7f0f354b297e8914ab240"
```
