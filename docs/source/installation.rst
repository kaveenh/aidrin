Installation Guide for AIDRIn
=============================

.. _installation:

Web Application Installation
----------------------------

.. note::

    The UI version of AIDRIn is currently in a private GitHub repository in `OSU's IDT Lab <https://github.com/idtlab>`_.

To install and run the UI version of AIDRIn, follow these steps:

### Step 1: Clone the Repository

Open your terminal (or command prompt on Windows) and run the following commands:

.. code-block:: shell

    $ git clone https://github.com/idtlab/AIDRIn.git
    $ cd aidrin

### Step 2: Create and Activate a Virtual Environment

#### On Linux or macOS

1. Create a virtual environment:

.. code-block:: shell

    $ python3 -m venv .venv

2. Activate the virtual environment:

.. code-block:: shell

    $ source .venv/bin/activate

#### On Windows

1. Create a virtual environment:

.. code-block:: shell

    $ py -3 -m venv .venv

2. Activate the virtual environment:

.. code-block:: shell

    $ .venv\Scripts\activate.bat

#### Using Conda (Cross-Platform)

1. Create a Conda environment:

.. code-block:: shell

    $ conda create --name aidrin python=3.11

2. Activate the Conda environment:

.. code-block:: shell

    $ conda activate aidrin

### Step 3: Install AIDRIn Dependencies

Inside the activated environment, install the dependencies:

.. code-block:: shell

    $ pip install -e .

### Step 4: Run the Application

Start the application using Flask:

.. code-block:: shell

    $ flask --app aidrin run --debug

Open your browser and go to `http://127.0.0.1:5000 <http://127.0.0.1:5000>`_.

PyPI Package Installation
-------------------------

To install and use the PyPI package version of AIDRIn, follow these steps:

### Step 1: Create and Activate a Virtual Environment

#### On Linux or macOS

1. Create a virtual environment:

.. code-block:: shell

    $ python3 -m venv .venv

2. Activate the virtual environment:

.. code-block:: shell

    $ source .venv/bin/activate

#### On Windows

1. Create a virtual environment:

.. code-block:: shell

    $ py -3 -m venv .venv

2. Activate the virtual environment:

.. code-block:: shell

    $ .venv\Scripts\activate.bat

#### Using Conda (Cross-Platform)

1. Create a Conda environment:

.. code-block:: shell

    $ conda create --name aidrin python=3.11

2. Activate the Conda environment:

.. code-block:: shell

    $ conda activate aidrin

### Step 2: Install AIDRIn from PyPI

Install the AIDRIn package from PyPI:

.. code-block:: shell

    $ pip install -i https://test.pypi.org/simple/ aidrin==X

.. note::

    Replace `X` with the latest version number. For example:

    .. code-block:: shell

        $ pip install -i https://test.pypi.org/simple/ aidrin==0.6.4
