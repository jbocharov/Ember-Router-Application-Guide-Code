Ember-Router-Application-Guide-Code
===================================

An repo of commits going from a basic Ember environment to a full application that uses Ember's Router

# USAGE

1.  Clone this repository
1.  cd `Ember-Router-Application-Guide-Code`
1.  `git submodule init` 
1.  `git submodule update` 
1.  cd `workspace`
1.  `bundle install`
1.  `rake`

You should now have a server running on port :4567.  Have fun exploring Ember!

# Background

This repository is built on [Halbert](https://github.com/sgharms/Halbert), a
tool I wrote to help get "scratch pad" applications up and running without the
involvement of JSFiddle or similar.

# Troubleshooting

I do most of my work on a VPS, this requries me to change `workspace/prod.yml`
so that the `address` attributes matches my hostname.  For those downloading
this application to localhost, it should not be an issue.

