Useful commands

.. code-block:: bash
    :linenos:
    
    pyenv install 3.6.0
    pyenv install 3.5.2
    pyenv versions
    pyenv version
    pyenv global 3.5.2 # set current global python version

    # change the python version for the current shell
    pyenv shell 3.6.0
    pyenv shell --unset # restore to the original python version
    
    # multiple local python versions
    # pyenv local 3.5.2 3.6.0

    # create virtual environment for the pelican project
    # pyenv virtualenv 3.5.2 pelican
