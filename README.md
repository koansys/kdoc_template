#### Clone 

    $ git clone git@github.com:koansys/kdoc_template.git kdocs
    $ cd kdocs

#### Create venv

    $ virtualenv . --distribute
 
#### install sphinx

    $ ./bin/easy_install sphinx

#### build docs

    $ . bin/activate
    $ make html

#### See sphinx docs

The section on theming

http://sphinx.pocoo.org/theming.html

more specifically:

http://sphinx.pocoo.org/theming.html#creating-themes
