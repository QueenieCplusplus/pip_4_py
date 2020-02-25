# pip_4_py
PIP


<h1> Queen PiP

pip is a useful package manager for Python.

# Installation of PiP

while installing the python engine (and add Path in Env), the PiP package manager is also included.

# to check Version of PiP

$ pip -V (upper case)

$ pip --version

# Upgrade for PiP or other site pkg

$ pip install -u < site_pkg >

$ pip install pip --upgrade

$ pip install --upgrade pip

$ pip install < site_pkg > --upgrade

<http://blog.e-happy.com.tw/python-%E5%A6%82%E4%BD%95%E6%9B%B4%E6%96%B0-pip-%E5%88%B0%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%EF%BC%9F/>

# Install a lot of Dependecies at a time

see the structure of root pkg (as a folder)

see their relationship amongs sites pkg and dependencies

    $ pip install -r < file_name > . < extention_name >

    $ pip install -r requirements.txt

# CMD of PiP

    $ cd < root pkg >

    $ pip install < 3rd party pkg or dependencies>

    //$ python -m install pip < 3rd party pkg or dependencies>

# to check all the pkgs installed in the root PKG

    $ pip list

example:

        Package            Version    
        ------------------ -----------
        aniso8601          8.0.0
        attrs              19.3.0
        certifi            2019.3.9
        chardet            3.0.4
        Click              7.0
        comtypes           1.1.7
        derpy              0.1.1
        Flask              1.1.1
        flask-restplus     0.12.1
        Flask-Session      0.3.1
        Flask-SQLAlchemy   2.4.1
        idna               2.8
        importlib-metadata 1.5.0
        itsdangerous       1.1.0
        Jinja2             2.11.1
        jsonschema         3.2.0
        MarkupSafe         1.1.1
        numpy              1.18.1
        pandas             1.0.1
        pdfminer3          2018.12.3.0
        pip                20.0.2
        pycryptodome       3.9.6
        PyMySQL            0.9.3
        PyPDF4             1.27.0
        pyrsistent         0.15.7
        python-dateutil    2.8.1
        pytz               2019.3
        pywin32            227
        requests           2.22.0
        scipy              1.4.1
        setuptools         41.2.0
        six                1.14.0
        sortedcontainers   2.1.0
        SQLAlchemy         1.3.13
        urllib3            1.25.8
        Werkzeug           0.16.0
        xlrd               1.2.0
        XlsxWriter         1.2.7
        xlwings            0.18.0
        zipp               2.2.0

# to check the relationship for PKG and Its Dependencies

    $ pip show < dependency_name >

example:

        pip show Werkzeug
        Name: Werkzeug
        Version: 0.16.0
        Summary: The comprehensive WSGI web application library.
        Home-page: https://palletsprojects.com/p/werkzeug/
        Author: Armin Ronacher
        Author-email: armin.ronacher@active-4.com
        License: BSD-3-Clause
        Location: c:\users\109009\appdata\local\programs\python\python37\lib\site-packages       
        Requires:
        Required-by: Flask

# Help

    $ pip help install

# Hot Keys to see Historical Log

press tab

press ↑

press ↓

# rare usage

    $ pip install < pkg_name > --no-deps    
    
Don't install package dependencies.

# Useful Link

<https://pip.pypa.io/en/stable/reference/pip_install/>
