# Scala Documentation #

This repository contains the source for the Scala documentation website, as well as the source for "Scala Improvement Process" (SIP) documents. 

## Dependencies ##

Jekyll is required. Follow the install instructions at the Jekyll [wiki](https://github.com/mojombo/jekyll/wiki/Install). In most cases, you can install via RubyJems: 

    gem install jekyll

OSX users might need to update RubyGems:

    sudo gem update --system

## Building & Viewing ##

cd into the `scala-docs` directory, and build by:

    jekyll --server --base-url '/scala-docs'

The generated site is available at `http://localhost:4000/scala-docs/`





