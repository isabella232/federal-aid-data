# federal-aid-data
Data exploration of the federal aid data from the department of education

Assumptions
-----------

The following things are assumed to be true in this documentation.

* You are running OSX.
* You are using Python 2.7. (Probably the version that came OSX.)
* You have [virtualenv](https://pypi.python.org/pypi/virtualenv) and [virtualenvwrapper](https://pypi.python.org/pypi/virtualenvwrapper) installed and working.
* You have NPR's AWS credentials stored as environment variables locally.

Bootstrap the project
---------------------

```
cd name-of-project
mkvirtualenv name-of-project
pip install -r requirements.txt
```

**Problems installing requirements?** You may need to run the pip command as ``ARCHFLAGS=-Wno-error=unused-command-line-argument-hard-error-in-future pip install -r requirements.txt`` to work around an issue with OSX.

Run the notebook
---------------

`
jupyter notebook
`

The homepage of the notebook should open automatically in your preferred browser. Notebooks generally run on `localhost:8888` if it is the sole notebook running.

Sources
-------

[Federal Student Loan Portfolio](https://studentaid.ed.gov/sa/about/data-center/student/portfolio)
[Default Management](https://ifap.ed.gov/DefaultManagement/DefaultManagement.html)
[Default Management definitions](https://www2.ed.gov/offices/OSFAP/defaultmanagement/instructions.html) 
