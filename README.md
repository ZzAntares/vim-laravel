# vim-laravel

This Vim plugin provides a set of helpers to use the `artisan` command within
vim to create new resources or to execute any artisan command, it also provides
helpers to open the most common resources such as commands, controllers, models,
etc.

# Installation

Using vundle you need to add something like this to your .vimrc

```
Plugin 'ZzAntares/vim-laravel'
```

Then save your changes, source the file and install:
```
:w
:source %
:PluginInstall
```

Thats it, now when your vim's pwd is set to a laravel 5 project (where the
artisan file is) you can use the plugin's functions.

# Usage

`:help vim-laravel`
