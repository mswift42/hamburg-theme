# hamburg-theme
Emacs Color Theme with a dark background.

Created with [ThemeCreator](https://github.com/mswift42/themecreator).

### Screenshots:
Python and Ruby:
![Screenshot ](https://github.com/mswift42/hamburg-theme/raw/master/emacshamburgpyruby.png)

Javascript and Clojure:
![Screenshot ](https://github.com/mswift42/hamburg-theme/raw/master/emacshamburgjsclojure.png)

* * * 

Available on Melpa.

Installation Instructions
-------------------------

add the following lines to your init.el (only if you have not done so already):

    (setq package-archives '(("gnu" . "http://elpa.gnu.org/packages/")
                             ("melpa" . "http://melpa.org/packages/")))
    (package-initialize)



This will add the gnu and melpa repos to your emacs setup.

To install the theme:

**M-x package-install** hamburg-theme


To use the hamburg theme when starting emacs, add this to your init.el:

    (load-theme 'hamburg)
