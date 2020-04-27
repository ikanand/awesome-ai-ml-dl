# Programming in Python

- [Basics / Learning](#basics-learning)
- [Intermediate / Advanced Python](#intermediate-advanced-Python)
- [Cheatsheets](#cheatsheets)
- [Static analysis](#static-analysis)
    - [Focussed packages](#focussed-packages)
    - [Python Wrappers](#python-wrappers)
- [Cookie cutter: Python project templates](#cookie-cutter-python-project-templates)
- [Frameworks](#frameworks)
- [Best practices](#best-practices)
- [Testing](#testing)
- [Refactoring](#refactoring)
- [Performance](#performance)
- [Contributing](#contributing)

## Basics / learning

- [Python Fundamentals](https://github.com/virgili0/Virgilio/blob/master/serving/purgatorio/fundamentals/python-fundamentals/python-fundamentals.md)
- [Lists, Tuples, Dictionaries, Conditionals, Loops, etc...](https://lnkd.in/gWRbc3J)
- [Data Structures & Algorithms](https://lnkd.in/gYKnJWN)
- [NumPy Arrays](https://lnkd.in/geeFePh)
- [Regex](https://lnkd.in/gzUahNV)
- [Introduction to Python](https://simpliv-wordpress-com.cdn.ampproject.org/c/s/simpliv.wordpress.com/2019/06/27/best-way-to-learn-python-step-by-step-guide/amp/)
- [Learn Python](https://www.learnpython.org/)
- [Python 3 Tutorial](https://docs.python.org/3/tutorial/)
- Online Python REPLs & Editors
  - [Python 2](https://repl.it/languages/Python2)
  - [Python 3](https://repl.it/languages/Python3) 
  - [Coding Ground: Execute Python Online (Python v2.7.13)](https://www.tutorialspoint.com/execute_python_online.php)
  - [The 10 Best Tools to Edit and Compile Python](https://noeticforce.com/python-online-compiler-interpreter-code-editors)
  - [9 Online Interactive Shells to Write Python Anywhere](https://www.bettertechtips.com/internet/python-shell-online/)
  - [Online Python Turtle Editor](https://repl.it/languages/python_turtle)
  - [Online Python Compiler](https://www.onlinegdb.com/online_python_compiler)
- [Local machine: Interacting with Python](https://realpython.com/interacting-with-python/)
- [Python by Chris Albon](https://chrisalbon.com/#python) - topics covered: Basics • Data Wrangling • Data Visualization • Web Scraping • Testing • Logging • Other
- [Regex resources by Chris Albon](https://chrisalbon.com/#regex)
- [WTF Python repo](https://github.com/satwikkansal/wtfpython)
- [Introduction to Python](https://github.com/Imperial-College-Data-Science-Society/Lecture-1-Intro-to-Python)
- [Introduction of Python Programming](https://www.linkedin.com/posts/nabihbawazir_python-self-study-activity-6605392829378367488-Q6Uz)
- [Writing your first program in Python (2019) - Brown University](https://www.linkedin.com/posts/nabihbawazir_introductions-to-python-activity-6606104345299771392-t7f1)

## Intermediate / Advanced Python

- [Numpy  *****QUICK REFERENCE*****](https://www.linkedin.com/posts/asif-bhat_numpy-cheat-sheet-activity-6633320071966089217-bu96)
- [Python to Numpy](https://www.labri.fr/perso/nrougier/from-python-to-numpy/)
- [100 Exercises ✅ Numpy ✅](https://www.linkedin.com/posts/asif-bhat_100-numpy-exercises-activity-6633319536751939584-hvfu)
- [Scientific Python](https://github.com/Imperial-College-Data-Science-Society/Lecture-2-Scientific-Python)
- [Neural Networks Matrices exploration - Under the Hood Mathematical Operations](https://github.com/souravs17031999/NeuralNets-Pure-Python)
- [Understand the use of *args and **kwargs](https://morioh.com/p/252b73e0be0a?f=5c21f93bc16e2556b555ab2f&fbclid=IwAR2P_D8kr9Gf2gCjd2pf57ugkuv0qBfG0JEuAijGgl3JE2o_N1_MVk7u8CM)
- [Here are some great Python Resources to learn #DataScience and #MachineLearning](https://www.linkedin.com/posts/asif-bhat_datascience-machinelearning-activity-6638314806367621120-vWp0)
- [👉 🐍Machine Learning Projects with Python 🐍👈](https://www.linkedin.com/posts/asif-bhat_machine-learning-projects-activity-6643602873957605376-5VJ4)

## Courses

See **Python: Best practices** and **Python: Testing** under [Courses](./courses.md#course)

## Cheatsheets

- [Python Cheatsheet](https://www.pythoncheatsheet.org/)
- [PySheee: Python Cheatsheet](https://www.pythonsheets.com/)
- [7+ Python Cheat Sheets for Beginners and Experts](https://sinxloud.com/python-cheat-sheet-beginner-advanced/)
- [Python for Data Science](https://s3.amazonaws.com/assets.datacamp.com/blog_assets/PythonForDataScience.pdf)
- [30 seconds of python](https://github.com/30-seconds/30-seconds-of-python)

## Database

### Databases implemented in python

- [Pickle DB](https://pythonhosted.org/pickleDB/)
- [Tinydb](https://github.com/msiemens/tinydb)
- [ZODB](http://www.zodb.org/en/latest/)

## Static analysis

### Focussed packages

* [mccabe](https://github.com/PyCQA/mccabe) - check McCabe complexity
* [mypy](https://github.com/python/mypy) - a static type checker that aims to combine the benefits of duck typing and static typing, frequently used with [MonkeyType](https://github.com/Instagram/MonkeyType)
* [py-find-injection](https://github.com/uber/py-find-injection) - find SQL injection vulnerabilities in Python code
* [pycodestyle](https://github.com/PyCQA/pycodestyle) - (formerly `pep8`) check Python code against some of the style conventions in PEP 8
* [pydocstyle](https://github.com/PyCQA/pydocstyle) - check compliance with Python docstring conventions
* [pyflakes](https://github.com/pyflakes/pyflakes/) - check Python source files for errors
* [pylint](https://github.com/PyCQA/pylint) - looks for programming errors, helps enforcing a coding standard and sniffs for some code smells. It additionally includes `pyreverse` (an UML diagram generator) and `symilar` (a similarities checker).
* [pyre-check](https://github.com/facebook/pyre-check) - A fast, scalable type checker for large Python codebases
* [pyright](https://github.com/Microsoft/pyright) - Static type checker for Python, created to address gaps in existing tools like mypy.
* [pyroma](https://github.com/regebro/pyroma) - rate how well a Python project complies with the best practices of the Python packaging ecosystem, and list issues that could be improved
* [PyT - Python Taint](https://github.com/python-security/pyt) - A static analysis tool for detecting security vulnerabilities in Python web applications.
* [pytype](https://github.com/google/pytype) - A static type analyzer for Python code.
* [Review of Python Static Analysis Tools](https://www.codacy.com/blog/review-of-python-static-analysis-tools/)
* [Python Static Analysis Tools ](https://luminousmen.com/post/python-static-analysis-tools)
* [PANDAS  👉 Reading and Writing Data 👈](https://www.linkedin.com/posts/asif-bhat_pandas-activity-6610445263372947456-oxup)
* See [awesome-static-analysis for Python](https://github.com/mre/awesome-static-analysis/blob/master/README.md#python)

### Python wrappers

* [ciocheck](https://github.com/ContinuumIO/ciocheck) - linter, formatter and test suite helper. As a linter, it is a wrapper around `pep8`, `pydocstyle`, `flake8`, and `pylint`.
* [flake8](https://github.com/PyCQA/flake8) - a wrapper around `pyflakes`, `pycodestyle` and `mccabe`
* [multilint](https://github.com/adamchainz/multilint) - a wrapper around `flake8`, `isort` and `modernize`
* [prospector](https://github.com/PyCQA/prospector) - a wrapper around `pylint`, `pep8`, `mccabe` and others

## Cookie cutter: Python project templates

- [For Python projects](https://cookiecutter.readthedocs.io/en/latest/readme.html#python)
- [For Data Science projects](https://cookiecutter.readthedocs.io/en/latest/readme.html#data-science)
- [For Reproducible Data Science projects](https://cookiecutter.readthedocs.io/en/latest/readme.html#reproducible-science)
- [For Data Driven Journalism projects](https://cookiecutter.readthedocs.io/en/latest/readme.html#data-driven-journalism)

## Frameworks

- [streamlit.io](https://streamlit.io/) - the fastest way to build custom ML tools | [Docs](https://streamlit.io/docs) | [GitHub](https://github.com/streamlit/streamlit) | [Blog](https://towardsdatascience.com/coding-ml-tools-like-you-code-ml-models-ddba3357eace) | [Community](https://discuss.streamlit.io/)
  - Crash courses
    - [Getting started](https://youtu.be/_9WiB2PDO7k) | [source files](examples/python/frameworks/streamlit/)
    - [Creating an ML Explorer](https://youtu.be/_9WiB2PDO7k)
    - [Deploying to Heroku](https://www.youtube.com/watch?v=skpiLtEN3yk)
  - [Discussion forum](https://discuss.streamlit.io)
- Flask alternatives
  - [anvil.works](https://https://anvil.works/) - Full stack web apps
with nothing but Python
    - [Learn](https://anvil.works/learn)
        - [Tutorial](https://anvil.works/learn/tutorials#features)
        - [HTTP APIs in python](https://anvil.works/learn/tutorials/http-apis-in-python)
            - [HTTP APIs in python: Authentication](https://anvil.works/learn/tutorials/http-apis-in-python#authentication)
            - [HTTP APIs in python: accepting params](https://anvil.works/learn/tutorials/http-apis-in-python#accepting-parameters)
            - [HTTP APIs in python: URL params](https://anvil.works/learn/tutorials/http-apis-in-python#url-parameters)
        - [App Secrets](https://anvil.works/learn/tutorials/app-secrets) 
        - [Crash course on create web apps using Anvil](https://training.talkpython.fm/courses/explore_anvil/anvil-web-apps-with-just-python)
        - [Security](https://anvil.works/docs/security)
    - [Forum](https://anvil.works/forum/)
  - [Assembly](https://mardix.github.io/assembly/) - A Pythonic Object-Oriented Web Framework built on Flask
- [A curated list of awesome Python frameworks, libraries, software and resources](https://github.com/vinta/awesome-python)
- [Explanation of most popular Data Science Library (in Python)](https://www.linkedin.com/posts/nabihbawazir_artificialintellegence-datascience-machinelearning-activity-6617700382200164352-RDhs)
- [50 most popular Python libraries and frameworks used in data science](https://www.linkedin.com/posts/nabihbawazir_python-datascience-dataanalysis-activity-6604589510447722496-AvyE)
- [Python for 9 Purposes: The graphics miss Scikit-Learn and of course "Pandas"](https://www.linkedin.com/posts/nabihbawazir_python-for-9-purposesthe-graphics-miss-scikit-learn-activity-6605860742774259712-Was0)
- [Free python tools](https://www.linkedin.com/posts/nabihbawazir_datascience-machinelearning-artificialintelligence-activity-6627149341998051328-oqZr)
- [Tips N Tricks: 3 Simple and Easy Ways to Cache Functions in Python](https://www.youtube.com/watch?v=H_FDL0oRAWE)
- [A simple video that explains in a very simple way how you can use joblib to speed up almost any function](https://www.youtube.com/watch?v=Ny3O4VpACkc)

## Best practices

- [PEP 8 -- Style Guide for Python Code](https://www.python.org/dev/peps/pep-0008/)
- [Python Best Practices and Tips by Toptal Developers](https://www.toptal.com/python/tips-and-practices)
- [Python Best Practices for More Pythonic Code](https://realpython.com/tutorials/best-practices/)
- [Python String Formatting Best Practices](https://realpython.com/python-string-formatting/)
- [The Best of the Best Practices (BOBP) Guide for Python](https://gist.github.com/sloria/7001839)
- [Dmitry Mugtasimov's Python software development practices](https://dmugtasimov-tech.blogspot.com/2016/12/my-python-software-development-practices.html)
- [SO: Python coding standards/best practices](https://stackoverflow.com/questions/356161/python-coding-standards-best-practices)
- [Python Best Practices: 5 Tips For Better Code - Airbrake Blog](https://airbrake.io/blog/python/python-best-practices)
- [Python tutorial: Best practices and common mistakes to avoid](https://jaxenter.com/python-tutorial-best-practices-145959.html)
- [Common mistakes beginnners make in python](https://github.com/qxf2/wtfiswronghere)
- [Six steps to more professional data science code notebook on Kaggle by Rachael Tateman](https://kaggle.intercom-mail.com/via/e?ob=ktkgCmdq8TTLcC0KcRnaTDrpfyNmo93hWgJS%2Bf3C%2FpeXDMn5IliXwMPCgGeVFtngYeGLq2r3zzpfPOt1R2SLUvPz%2BOZl6ye5CNrx98D279Mjy%2BDCxeLTcN3rL%2BXuXvYPwdMeFoEliM4ujTLctPU1Rb2Kt8AOwN30PYPGdMZPPhxkha%2BlQ9oixCrQILf%2BWqOTvh59huu9yn%2BqmDKPk9wcnA%3D%3D&h=6b05c8a50ab9ff60c7c061020cc5428a92dce16c-23895383563) | [Video: 6 Steps for More Professional Data Science Code | Kaggle](https://www.youtube.com/watch?v=Trar7GZOPl8&feature=youtu.be&utm_medium=email&utm_source=intercom&utm_campaign=modular-code-event) | [Import scripts into notebook kernels](https://www.kaggle.com/product-feedback/91185) | [Kaggle Live Coding: Making code modular | Kaggle](https://www.youtube.com/watch?v=5zgxMgG4A7o) | [Documentation on Python modules](https://docs.python.org/3/tutorial/modules.html) | [DocStrings](https://www.python.org/dev/peps/pep-0257/) | [Don't Repeat Yourself (DRY)](https://en.wikipedia.org/wiki/Don%27t_repeat_yourself) | [PEP 8](https://www.python.org/dev/peps/pep-0008/) | [Joy of Functional programming for Data Science](https://www.youtube.com/watch?v=bzUmK0Y07ck) | [Method Chaining in Python using pyjanitor](https://pyjanitor.readthedocs.io/notebooks/pyjanitor_intro.html#Clean-up-our-data-using-a-pyjanitor-method-chaining-pipeline) | [pyjanitor docs](https://pyjanitor.readthedocs.io/notebooks/pyjanitor_intro.html#Clean-up-our-data-using-a-pyjanitor-method-chaining-pipeline) | [Code reviewing Data Science work](https://medium.com/apteo/code-reviewing-data-science-work-774747248e33) | [Python built-in method: assert](https://docs.python.org/3/reference/simple_stmts.html#the-assert-statement) | [Code Smells](https://en.wikipedia.org/wiki/Code_smell) | [Kaggle Coffee Chat: Joel Grus | Kaggle: software engineering best practices](https://www.youtube.com/watch?v=Sg6xJ0ACc78) | [Scripting-your-data-validation notebook: Automating Data Pipelines](https://www.kaggle.com/rtatman/automating-data-pipelines-day-2#Scripting-your-data-validation) | [Dashboarding with Notebooks: Day 5](https://www.kaggle.com/rtatman/dashboarding-with-notebooks-day-5) | [Kaggle Scripts](https://www.kaggle.com/kernels?sortBy=hotness&group=everyone&pageSize=20&tagIds=16074) | [Regular Expressions](https://en.wikipedia.org/wiki/Regular_expression)
- Packages & Libraries: [Cerberus module](http://docs.python-cerberus.org/en/stable/usage.html) | [missingno package](https://github.com/ResidentMario/missingno) | [python-magic module](https://github.com/ahupp/python-magic) | [Python Flashtext](https://flashtext.readthedocs.io/en/latest/) | [Flashtext github](https://github.com/vi3k6i5/flashtext#why-not-regex) | [Forum post embeddings + clustering](https://www.kaggle.com/rtatman/forum-post-embeddings-clustering)
- [Jason Gormans'](https://twitter.com/jasongorman) Python Code Craft series:
  - [Code Craft : Part I – Why We Need Code Craft](https://codemanship.wordpress.com/2019/10/01/code-craft-part-i-why-we-need-code-craft/)
  - [Code Craft : Part II – Version Control is Seat Belts for Programmers](https://codemanship.wordpress.com/2019/10/02/code-craft-part-ii-version-control-is-seat-belts-for-programmers/)
  - [Code Craft : Part III – Unit Tests are an Early Warning System for Programmers](https://codemanship.wordpress.com/2019/10/04/code-craft-part-iii-unit-tests-are-an-early-warning-system-for-programmers/)

## Versioning

- [ML Versioning Tool](https://github.com/peopledoc/ml-versioning-tools) by [@sbracaloni](https://github.com/sbracaloni)

## Testing

- [Python Developer's Guide » Running & Writing Tests](https://devguide.python.org/runtests/)
- [Hitchhickers Guide to Python: Testing Your Code](https://docs.python-guide.org/writing/tests/)
- [SO: Writing unit tests in Python: How do I start?](https://stackoverflow.com/questions/3371255/writing-unit-tests-in-python-how-do-i-start)
- [Testing Python Applications with Pytest](https://semaphoreci.com/community/tutorials/testing-python-applications-with-pytest)
- [An Introduction to Mocking in Python](https://www.toptal.com/python/an-introduction-to-mocking-in-python)
- [PyCharm: Testing Your First Python Application](https://www.jetbrains.com/help/pycharm/testing-your-first-python-application.html)
- [unittest — Unit testing framework](https://docs.python.org/2/library/unittest.html)

### Machine Learning

See [Machine Learning Testing](./details/julia-python-and-r.md#testing)

## Refactoring

- [PyCharm: Refactoring code](https://www.jetbrains.com/help/pycharm/refactoring-source-code.html)
- [PyCharm refactoring tip](https://stackoverflow.com/questions/47978893/pycharm-is-this-kind-of-automatic-signature-refactoring-possible)
- [PyCharm Refactoring Tutorial](https://www.jetbrains.com/help/pycharm/product-refactoring-tutorial.html)
- [Learning Python with PyCharm: Refactoring](https://www.lynda.com/Python-tutorials/Refactoring/590828/629432-4.html)
- [What refactoring tools do you use for Python?](https://stackoverflow.com/questions/28796/what-refactoring-tools-do-you-use-for-python)
- [Bowler: Safe code refactoring for modern Python projects](https://github.com/facebookincubator/Bowler) - Bowler is a refactoring tool for manipulating Python at the syntax tree level. It enables safe, large scale code modifications while guaranteeing that the resulting code compiles and runs.

## Performance

- [Python High Performance - Second Edition](https://github.com/PacktPublishing/Python-High-Performance-Second-Edition)
- [Python and performance](https://github.com/ameroueh/performance)
- [NumPy aware dynamic Python compiler using LLVM ](https://github.com/ameroueh/numba) | [Numba](http://numba.pydata.org/)
- [Profiling in Python](https://github.com/mkunesch/profiling-talk) - by [Markus Kunesch](https://github.com/mkunesch)
- High Performance Python talk by [Ian Oszvald](https://twitter.com/ianozsvald/): Blogs: [1](https://ianozsvald.com/2019/11/16/higher-performance-python-at-pydatacambridge-2019/) o [2](https://ianozsvald.com/2019/11/22/higher-performance-python-odsc-2019/)  | [Slides](https://speakerdeck.com/ianozsvald/higher-performance-python-odsc-2019) | [Useful resources shared](https://twitter.com/DataChaz/status/1197608275606413312)

## Competitions & coding challenges

See [Competitions > Coding challenges](./competitions.md#coding-challenges)

# Contributing

Contributions are very welcome, please share back with the wider community (and get credited for it)!

Please have a look at the [CONTRIBUTING](CONTRIBUTING.md) guidelines, also have a read about our [licensing](LICENSE.md) policy.

---

Back to [main page (table of contents)](README.md)