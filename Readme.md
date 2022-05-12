# Django + Tailwind

This is example how to setup [Django](https://www.djangoproject.com/) with
[Tailwind CSS framework](https://tailwindcss.com/).

### Requirements

1. Python 3.4 || Python 3.5
2. Node.js
3. [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/) - package
   managers
4. [pip](https://pypi.python.org/pypi/pip/1.0.2) - tool for installing and
   managing Python packages
5. [virtualenv](http://docs.python-guide.org/en/latest/dev/virtualenvs/) - tool
   to keep the dependencies required by different projects in separate places

### Installation

These commands are valid for **Mac/Ubuntu OS**. If you develop on Windows, you
should replace them with proper commands, If you are using the default Windows
Command Line.

1. Create virtual environment in your project folder <code>python3 -m venv
   venv</code>
2. Activate the virtual environment <code>source venv/bin/activate</code>
3. Install required libraries and packages <code>pip3 install -r
   requirements.txt</code>
4. Navigate to the project root
5. Install Tailwind <code>python3 manage.py tailwind install</code>
6. Setup path to your npm installation <code>which npm</code> (or yarn)
7. Setup ENV variable in <code>project/settings.py</code> <br />
   <code>NPM_BIN_PATH={your path}</code>
8. Install Tailwind dependencies <code>python3 manage.py tailwind install</code>
9. Migrate database <code>python3 manage.py migrate</code>
10. Run server <code>python3 manage.py runserver</code> in one terminal
11. Run Tailwind <code>python3 manage.py tailwind start</code> in another
    terminal
