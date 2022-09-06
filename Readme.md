[SimpleModal]() - A private industrydive fork of @ericmmartin's modal dialog framework for jQuery
================================

* [Documentation](http://www.ericmmartin.com/projects/simplemodal/)
* [Demos](http://www.ericmmartin.com/projects/simplemodal-demos/)

Building SimpleModal
--------------------

* Make sure that you have [Java](http://java.sun.com/javase/downloads/index.jsp) and [Ant](http://ant.apache.org/bindownload.cgi) installed.

In the main directory of the distribution (the one that this file is in), type the following to make all versions of SimpleModal:

    ant

The standard, uncompressed, SimpleModal code.  
Makes: `./dist/jquery.simplemodal.divefork.js`
This will also output a minified version.

    ant full

Finally, you can remove all the built files using the command:
  
    ant clean
