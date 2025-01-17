***************************************
Improved Nano Syntax Highlighting Files
***************************************

This repository holds ``{lang}.nanorc`` files that have improved
definitions of syntax highlighting for various languages.
These should be placed inside of the ``~/.nano/`` directory.
Alternatively::

    git clone git@github.com:vittee/nanorc.git ~/.nano
    
*Note - if you have any issues, alternatively use::

    git clone https://github.com/vittee/nanorc.git ~/.nano


Once there you should add the languages you want to your
nano configuration file ``~/.nanorc``.  For example::

    ## C/C++
    include "~/.nano/c.nanorc"

You can also append the contents of ``~/.nano/nanorc`` into your
``~/.nanorc`` to include all languages::

    cat ~/.nano/nanorc >> ~/.nanorc
