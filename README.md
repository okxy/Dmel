#Contents
* [Beginner's Delight](#beginners-delight)
* [Style Guide and Idioms](#style-guide-and-idioms)
* [Dictionary](#dictionary)
* [Decorators](#decorators)
* [Generators](#generators)
* [Iterators](#iterators)
* [Yield](#yield)
* [Context Managers](#context-managers)
* [Unicode](#unicode)
* [Networking](#networking)
* [Metaclasses](#metaclasses)
* [Documentation](#documentation)
    * [Sphinx](#sphinx)
* [Debugging](#debugging)
    * [Logging](#logging)
* [Testing](#testing)
* [Environment and Environment Management](#environment-and-environment-management)
* [Profiling](#profiling)
* [Packaging](#packaging)
* [Deployment](#deployment)
    * [Fabric](#fabric)
* [Warts and Gotchas](#warts-and-gotchas)
* [Web](#web)
    * [Frameworks](#frameworks)
        * [Flask](#flask)
        * [Web2Py](#web2py)
        * [Django](#django)
        * [Bottle](#bottle)
    * [API and Web Services](#api-and-web-services)
    * [Scraping](#scraping)

* [Miscellaneous](#miscellaneous)


##Beginner's Delight
* [Beginner's guide to Python](http://wiki.python.org/moin/BeginnersGuide)
* [The Hitchhiker's guide to Python](http://docs.python-guide.org/en/latest/)
* [Learn Python the hard way](http://learnpythonthehardway.org/book/)
* [Google's Python class](https://developers.google.com/edu/python/)
* [Python tracks at Codecademy](http://www.codecademy.com/tracks/python)
* [Python Monk](http://pythonmonk.com/)
* [Python for Beginners](http://www.pythonforbeginners.com/)
* [Best way to learn python](http://net.tutsplus.com/tutorials/the-best-way-to-learn-python/)
* [Python Tips, tools and resources](http://lurnq.com/lesson/Getting-started-with-Python-Tips-Tools-and-Resources)
* [Python Koans: Learn Python through TDD](https://github.com/gregmalcolm/python_koans)
* [LearnStreet Python course](http://www.learnstreet.com/lessons/study/python)
* [Beginner projects for a python newbie](http://newcoder.io/)
* [Learn X in Y minutes - Python](http://learnxinyminutes.com/docs/python/)
* [Python Practice book](http://anandology.com/python-practice-book/)
* [Facts and myths about Python names and values](http://nedbatchelder.com/text/names.html)
* [*args and **kwargs in python explained](http://freepythontips.wordpress.com/2013/08/04/args-and-kwargs-in-python-explained/)
* [Common newbie mistakes in Python- Part 1](http://blog.amir.rachum.com/post/54770419679/python-common-newbie-mistakes-part-1)
* [Common newbie mistakes in Python- Part 2](http://blog.amir.rachum.com/post/55024295793/python-common-newbie-mistakes-part-2)
* [PySchools](http://www.pyschools.com/)
* [Some cool Python Tricks](http://www.quora.com/Python-programming-language-1/What-are-some-cool-Python-tricks)
* http://blog.amir.rachum.com/post/30176371115/you-cant-handle-the-truth
* [Better Python APIs](http://ozkatz.github.io/better-python-apis.html)
* [Declaring dependencies in Python](http://blog.ziade.org/2013/04/13/declaring-dependencies-in-python/)
* [Storing and Loading Data with JSON - Serialization/deserialization](http://freepythontips.wordpress.com/2013/08/08/storing-and-loading-data-with-json/)
* [A Guide to Python's Magic Methods](http://www.rafekettler.com/magicmethods.html)
* [Efficient String Concatenation in Python](http://www.skymind.com/~ocrow/python_string/)
* [Be Pythonic: __init__.py](http://mikegrouchy.com/blog/2012/05/be-pythonic-__init__py.html)
* [Building an open-source Python application the right way](http://kirang.in/2013/09/09/building-an-open-source-python-application-the-right-way/)
* [Python progression path - From apprentice to guru](http://stackoverflow.com/questions/2573135/python-progression-path-from-apprentice-to-guru)
* [Learn python through Test Driven Development](https://github.com/gregmalcolm/python_koans)

##Style Guide and Idioms
* [PEP 8 - Style Guide for Python Code](http://www.python.org/dev/peps/pep-0008/)
* [Code Like a Pythonista: Idiomatic Python](http://python.net/~goodger/projects/pycon/2007/idiomatic/handout.html)

##Dictionary
* [Python hash, id and dictionary order](http://blog.amir.rachum.com/post/54458435089/python-hash-id-and-dictionary-order)
* [Notes on dictionary implementation](http://bugs.python.org/file6941/dictnotes.txt)
* [Python: The Dictionary Playbook](http://blog.amir.rachum.com/post/39501813266/python-the-dictionary-playbook)

##Decorators
* [Understanding Python Decorators in 12 easy steps](http://simeonfranklin.com/blog/2012/jul/1/python-decorators-in-12-steps/)
* [Common uses of Python decorators - Quora](http://www.quora.com/Python-programming-language-1/What-are-common-uses-of-Python-decorators)
* [Common uses of Python decorators - Stack Overflow](http://stackoverflow.com/questions/489720/what-are-some-common-uses-for-python-decorators)
* [Python Decorators](http://pythonconquerstheuniverse.wordpress.com/2012/04/29/python-decorators/)
* [Decorators I: Introduction to Python Decorators](http://www.artima.com/weblogs/viewpost.jsp?thread=240808)
* [Decorators and annotations](http://blog.mattalcock.com/2013/1/5/decorates-and-annotations/)
* [The dark side of decorators](http://apiguy.github.io/blog/2013/06/03/the-dark-side-of-decorators/)
* [Thinking out aloud: Python decorators](http://curiosityhealsthecat.blogspot.in/2013/06/thinking-out-aloud-python-decorators_8528.html)
* [Using Python decorators for registering callbacks](http://curiosityhealsthecat.blogspot.in/2013/07/using-python-decorators-for-registering_8614.html)
* [Meta-matters: Using decorators for better Python programming](http://pydanny-event-notes.readthedocs.org/en/latest/PyconAU2011/decorators.html)
* [How can I make a chain of function decorators in Python?](http://stackoverflow.com/questions/739654/how-can-i-make-a-chain-of-function-decorators-in-python/1594484#1594484)
* [The Python Decorator Library](https://wiki.python.org/moin/PythonDecoratorLibrary)

##Generators
* [Generator Tricks for Systems Programmers](http://www.dabeaz.com/generators-uk/)
* [Delegating to a Subgenerator in Python 3](http://docs.python.org/3/whatsnew/3.3.html#pep-380-syntax-for-delegating-to-a-subgenerator)

##Iterators
* [Understanding Iterators and Iterables](http://www.shutupandship.com/2012/01/understanding-python-iterables-and.html)

##Yield
* [Python yield keyword explained](http://stackoverflow.com/questions/231767/the-python-yield-keyword-explained)

##Context Managers
* [Understanding Python's with statement](http://effbot.org/zone/python-with-statement.htm)
* [The Python "with" Statement by Example](http://preshing.com/20110920/the-python-with-statement-by-example/)

##Unicode
* [Explain Unicode like I'm five years old](http://www.reddit.com/r/Python/comments/1g62eh/explain_it_like_im_five_python_and_unicode/)
* [Unicode Pain](http://nedbatchelder.com/text/unipain.html)
* [Python encodings and Unicode](http://eric.themoritzfamily.com/python-encodings-and-unicode.html)
* [The Updated Guide to Unicode on Python](http://lucumr.pocoo.org/2013/7/2/the-updated-guide-to-unicode/)

##Networking
* [An intro to Python socket network programming](http://freepythontips.wordpress.com/2013/08/06/python-socket-network-programming/)

##Metaclasses
* [A primer on python metaclasses](http://jakevdp.github.io/blog/2012/12/01/a-primer-on-python-metaclasses/)
* [What is a metaclass in Python ?](http://stackoverflow.com/questions/100003/what-is-a-metaclass-in-python)
* [Yet Another Python Metaclass tutorial](http://blog.fruiapps.com/2013/03/Yet-another-Python-MetaClass-Tutorial)

##Documentation
* [Documentation is King](http://kennethreitz.org/documentation-is-king/)
* [Make your open source project documentation suck less](http://kirang89.webfactional.com/2013/05/07/make-your-open-source-project-documentation-suck-less/)

###Sphinx
* [Quick Sphinx documentation for Python](http://scriptsonscripts.blogspot.in/2012/09/quick-sphinx-documentation-for-python.html)

## Environments and Environment Management
* [Virtual Environments — The Hitchhiker's Guide to Python](http://docs.python-guide.org/en/latest/dev/virtualenvs/)
* [Virtualenv Tutorial](http://simononsoftware.com/virtualenv-tutorial/)
* [A Primer on virtualenv](http://iamzed.com/2009/05/07/a-primer-on-virtualenv/)
* [How to use Python virtualenv](http://www.pythonforbeginners.com/basics/how-to-use-python-virtualenv)
* [Comprehensive beginner's virtualenv tutorial? - stackoverflow](http://stackoverflow.com/questions/5844869/comprehensive-beginners-virtualenv-tutorial)
* [Virtualenv - The official documentation](http://www.virtualenv.org/en/latest/)
* [Getting started with virtual env](http://iamzed.com/2009/05/07/a-primer-on-virtualenv/)
* [Extension to Virtualenv](https://bitbucket.org/dhellmann/virtualenvwrapper)
* [VirtualEnv Burrito = virtualenv + virtualenvwrapper](https://github.com/brainsik/virtualenv-burrito)

##Debugging
* [Debugging Tools in Python](http://blog.ionelmc.ro/2013/06/05/python-debugging-tools/)

###Logging
* [Sentry - realtime event logging and aggregation platform](https://sentry.readthedocs.org/en/latest/index.html)

##Testing
* [Nose Introduction](http://pythontesting.net/framework/nose/nose-introduction/)
* [Unittest Introduction](http://pythontesting.net/framework/unittest/unittest-introduction/)
* [How To Use Coverage.py With Unittest](https://github.com/audreyr/how-to/blob/master/python/use_coverage_with_unittest.rst)
* [An Extended Introduction to the nose Unit Testing Framework](http://ivory.idyll.org/articles/nose-intro.html)
* [Test strategies for your Python projects](http://blog.flaper87.com/post/522b9e560f06d32542ede77f/)

##Profiling
* [A guide to analyzing Python performance](http://www.huyng.com/posts/python-performance-analysis/)

##Packaging
* [The Hitchhiker’s Guide to Packaging](http://guide.python-distribute.org/)
* [Sharing Your Labor of Love: PyPI Quick And Dirty](http://hynek.me/articles/sharing-your-labor-of-love-pypi-quick-and-dirty/)
* [Open Sourcing a Python Project the Right Way](http://www.jeffknupp.com/blog/2013/08/16/open-sourcing-a-python-project-the-right-way/)
* [5 tips for packaging your Python projects](http://ziade.org/2011/08/19/5-tips-for-packaging-your-python-projects/)
* [AOSA: Python Packaging](http://www.aosabook.org/en/packaging.html)
* [The Package Dependency Blues](http://blog.miguelgrinberg.com/post/the-package-dependency-blues)
* [5 Simple Rules For Building Great Python Packages](http://axialcorps.com/2013/08/29/5-simple-rules-for-building-great-python-packages)
* [Unofficial Windows Binaries for Python Extension Packages](http://www.lfd.uci.edu/~gohlke/pythonlibs/)
* [Py2app: Standalone Mac OS X applications](http://pythonhosted.org/py2app/)
* [PyInstaller: Stand-alone executables, under Windows, Linux, Mac OS X, Solaris and AIX](http://www.pyinstaller.org/)



##Miscellaneous
* [enGrant Scientific](http://search.engrant.com/Results.aspx/)
* [How to Create Barcodes in Your PDFs with Python](http://java.dzone.com/articles/how-create-barcodes-your-pdfs)
* 

