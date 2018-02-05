# itamae-mitsurin-snippets

This is vim snippets for [itamae-mitsurin](https://rubygems.org/gems/itamae-mitsurin) inspired by [serverspec-snippets](https://github.com/hfm/itamae-snippets).

## Requirement

 * [Shougo/neosnippet.vim](https://github.com/Shougo/neosnippet.vim)

## Install

### Vundle

1. Setup the [vundle](https://github.com/gmarik/vundle) package manager
2. Set the bundles for [itamae-mitsurin-snippets](https://github.com/kammy1231/itamae-snippets)

``` vim
Bundle 'kammy1231/itamae-mitsurin-snippets'
```

3. Open up Vim and start installation with `:BundleInstall`

### Neobundle

1. Setup the [neobundle](https://github.com/Shougo/neobundle.vim) package manager
2. Set the bundles for [itamae-mitsurin-snippets](https://github.com/kammy1231/itamae-snippets)

``` vim
NeoBundle 'kammy1231/itamae-mitsurin-snippets'
```

3. Open up Vim and start installation with `:NeoBundleInstall`

## Setup

Set itamae-mitsurin-snippets directory(`~/.vim/bundle/itamae-snippets`) in your .vimrc.


``` vim
" setting example
let g:neosnippet#snippets_directory = [
      \'~/.vim/snippets',
      \'~/.vim/bundle/itamae-mitsurin-snippets',
      \]
```

### Usage

open itamae-mitsurin files and set filetype `ruby.itamae`

``` vim
:set ft=ruby.itamae-mitsurin
```

## License

Lcense: Same terms as Vim itself (see [license](http://vimdoc.sourceforge.net/htmldoc/uganda.html#license))
