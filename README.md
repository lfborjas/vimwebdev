VimWebDev: a community built vim configuration for python, ruby and node.js webdev projects
==============================================================================================

Here's a repo for posterity: I've found myself, to my utter bliss, working solely on vim and the command line in my node.js and sinatra projects, as well as with some non-django python related things, and thought that the having the configuration here might come in handy for anyone with similar needs. Even more, by having this public, someone might point out improvements and we could all benefit from them.

It includes third party plugins for haml, coffeescript and sass; assuming you have the system default syntax highlighting for ruby, python, javascript and regular html and css. There's also a rails plugin in there, but I haven't tested it and probably needs some tweaking.

I develop entire projects in vim mainly in ruby and javascript (node.js), and that's the reason why I have plugins related to those two here. If you feel this is a nice project but use other stuff for web development, feel free to fork and contribute!

Included Plugins
----------------

* For coffeescript, [vim-coffee-script](http://github.com/kchmck/vim-coffee-script)
* For haml and sass [haml.vim](http://www.vim.org/scripts/script.php?script_id=1433)
* For rails (untested) [rails.vim](http://www.vim.org/scripts/script.php?script_id=1567)
* For cool file navigation, [NERDTree](http://www.vim.org/scripts/script.php?script_id=1658)

Note that for the `NERDTree` plugin, the file `.vimrc.example` includes an example mapping of the `F2`key to avoid typing `:NERDTreeToggle` everytime you want to show/hide the NERDTree navigator.


How to use
-----------

Download the source and un(tar|zip) it in your ~/.vim folder. If you will, copy the contents of the file `.vimrc.example` to your `~/.vimrc` file for extra nifty stuff.

Contribute!
-----------

If you have alternative or better configurations for web development in node.js/python/ruby frameworks using vim for all edition, feel free to fork and send a pull request, adding to this file your contribution and how it enhances the awesomeness of vim based web development.

If you include plugins or configurations for web development based on DSLs other than node.js or ruby|python-based frameworks, please include a **good and detailed** reason here *and* in your pull request :)
