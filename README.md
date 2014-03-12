# About
===

This is a simple Rails 3.1 app that uses [parse_resource](http://github.com/adelevie/parse_resource) for model persistence and includes a simple auth system that's based on this [Railscast](http://asciicasts.com/episodes/250-authentication-from-scratch).

# Installation
===

    git clone git@github.com:jeffaburt/test-bench.git

    cd test-bench

    bundle install

    rails s

# Contributing Code
===

## Feature Branches

Since this is a small scale project, creating feature branches on this repository is completely fine - no need to create a fork unless you really want to.

When starting a new feature or fixing a bug, create a branch. Name the branch with a descriptive name.

    git checkout -b FEATURE-BRANCH-NAME

## Pull Requests

Once you have tested your changes and ready to submit, make sure you have merged in the latest code changes and then push to origin

    git pull origin master
    
*Resolve any merge conflicts*
    
    git push origin HEAD
    
***Note: HEAD is another way of saying "current branch name"***

Open a [Pull Request](https://github.com/jeffaburt/test-bench/compare) from the `master` branch to your new feature branch created above. Make sure the Pull Request is ready to merge.  If it is not, make sure you have the latest master merged into your feature branch.