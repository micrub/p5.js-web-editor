# adoption of `ctags` and language related configuration quirks

## JavaScript

By default, JavaScript support doesn't cope well with the modern implementation.
You’ll need to tell `ctags` how to parse all the new ways of declaring things, like:
(const, let, other method shorthand, etc...).
Thou, you still can use the expressions defined in this repo for a convenience.

## installation

### mac

```
brew install ctags-exuberant
cd
git clone git@github.com:micrub/ctags-patterns-for-javascript.git
cd ctags-patterns-for-javascript
pwd
/Users/current-username/personal-derctory/github/ctags-patterns-for-javascript
```

##### configuration change

Create a configuration file or add a path of current repo as follows into existing one:

```
--options=/Users/current-username/personal-derctory/github/ctags-patterns-for-javascript/ctagsrc"
```

restart `shell`.

# utils

## vim

### plugins

* https://github.com/ludovicchabant/vim-gutentags
* https://github.com/junegunn/fzf.vim




