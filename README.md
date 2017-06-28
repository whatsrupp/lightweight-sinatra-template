# Sinatra Template

This is a flyweight repository for those who want to make a quick Sinatra App but don't want to spend a whole 30 minutes of their life setting up the file structure and don't want to be overwhelmed by a sprawling horde of Rails files.

In fairness to Rails, the documentation is fantastic and it's a very powerful tool but it's just not appropriate for really basic apps.

Note, this isn't a Sinatra tutorial, I would recommend only using this once you understand the basic Model, View, Controller set up of web applications with Sinatra!

## Usage

I'm thinking about whacking this on Bundler as that could be quite a fun side project, however, to be fair, someone has probably already done it. For now, it'll have to sit as a repository based tool!

### Clone the repository

```
$  git clone  
```

### Link to your own repository

```
$ git remote set-url origin https://github.com/address/to/your/repository
```

### Gett'em them gems.
```
$ gem install bundler
$ bundle install
```

### Check it's working
```
$ rackup
```
You should see the following:
```
Puma starting in single mode...
* Version 3.9.1 (ruby 2.3.3-p222), codename: Private Caller
* Min threads: 0, max threads: 16
* Environment: development
* Listening on tcp://localhost:9292
```
Then checkout the localhost:

[http://localhost:9292/](http://localhost:9292/)

It should say 'Index Page'

### Change the naming conventions to fit your needs

Throughout the app there are references to 'App', simply rename this convention if
you feel the itch!


***

**_Thanks for reading and happy coding!_**

_Nick Rupp_
