# Yeoman Vagran Generator

A generator for [Yeoman](http://yeoman.io).

This is basically a `Vagrant init` on setroids

## Objective:

Add multiple built-in provisioning options to the basic Vagrantfile through an interactive Yeoman-based cli wizard


## Getting Started

### What is Yeoman?

Trick question. It's not a thing. It's this guy:


Basically, he wears a top hat, lives in your computer, and waits for you to tell him what kind of application you wish to create.

Not every new computer comes with a Yeoman pre-installed. He lives in the [npm](https://npmjs.org) package repository. You only have to ask for him once, then he packs up and moves into your hard drive. *Make sure you clean up, he likes new and shiny things.*

```
$ npm install -g yo
```



To install generator-vagrant from npm, run:

```
$ npm install -g generator-vagrant
```

Finally, initiate the generator:

```
$ yo vagrant
```

### Getting To Know Yeoman

Yeoman has a heart of gold. He's a person with feelings and opinions, but he's very easy to work with. If you think he's too opinionated, he can be easily convinced.

If you'd like to get to know Yeoman better and meet some of his friends, [Grunt](http://gruntjs.com) and [Bower](http://bower.io), check out the complete [Getting Started Guide](https://github.com/yeoman/yeoman/wiki/Getting-Started).

### Example Usage:
  
  ```
  yo vagrant
  
  Choose OS:
  (1) Ubuntu 12
  (2) Ubuntu 13
  (3) CentOS 6
  ...
  
  Choose Servlet Container:
  (1) Tomcat 6
  (2) Tomcat 7
  (3) Jetty
  (4) None
  
  Choose DB:
  (1) MySQL
  (2) MongoDB
  (3) Elasticsearch
  (4) Postgres
  ....
  
  Do you want another DB? y/N
  
  .....
  ets.
  ```


## License

[MIT License](http://en.wikipedia.org/wiki/MIT_License)
