# SPRUCE Solution Space Visualization

### DEPENDENCIES ###

* [**Bower**](http://bower.io/). You can install Bower using [NPM](https://www.npmjs.com/).

        npm install bower -g

### GETTING STARTED ###

0. After cloning this repository, install Bower and use it to install the Javascript dependencies:

        bower install

  This will create a directory `bower_components/`.

  2017/07/13: The most recent version of d3 is incompatible with the current script. As such, please do not perform this step and use the javascript libaries present in the repository.

1. Generate the HTML and JSON file by running:

        python generate.py ../../build/visualize solution.txt

2. Start the webserver using Python.

        python -m SimpleHTTPServer

3. Direct your browser to `http://localhost:8000/solution.txt.html`.

### ACKNOWLEDGMENTS

* Max Leiserson
* Mohammed El-Kebir
