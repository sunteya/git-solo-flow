git-solo-flow
=============

git-solo-flow is a simple git branching model, similar github-flow but use git difftool instead of pull request.

### Why not use [gitflow](https://github.com/petervanderdoes/gitflow)

gitflow is too complex, it could work well for version base projects. but most web app or small project not strict version they are always ready to released.

### Why not use [github-flow](https://github.com/github-flow/github-flow)

simply, github-flow only used for github user. and solo project don't need online pull request.

## Installation

Frist step, clone this project.

~~~~
git clone https://github.com/sunteya/git-solo-flow.git ~/.git-solo-flow
~~~~

Second step, add project `bin` to `$PATH`

~~~~
echo 'export PATH=$HOME/.git-solo-flow/bin:$PATH' >> ~/.profile
~~~~

done

## Usage

Usage is very similar to git-flow-feature, you can type `git solo-flow help` for more detail.

~~~~
usage: git solo-flow <subcommand>
Available subcommands are:
   start     Begin working on a new feature.
   finish    Merge and clean up branches.
   publish   Publish branch to origin.
   rebase    Update and rebase branch on origin master.
~~~~

## Note on Patches/Pull Requests

now you can use [github-flow](https://github.com/github-flow/github-flow) lol.

## Reference

[a simple git branching model](https://gist.github.com/jbenet/ee6c9ac48068889b0912)