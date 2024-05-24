Installation
============

.. _installation:

UI
------------

.. note::

    The UI version of AIDRIn is still a private GitHub repository in `OSU's IDT Lab <https://github.com/idtlab>`_.

To use the UI version of AIDRIn, first install using CLI:

Clone the repository:

.. code-block:: shell

    $ git clone https://github.com/idtlab/AIDRIn.git
    $ cd aidrin

Create a virtualenv and activate it:

.. code-block:: shell

    $ python3 -m venv .venv
    $ . .venv/bin/activate

Or on Windows cmd:

.. code-block:: shell

    $ py -3 -m venv .venv
    $ .venv\Scripts\activate.bat

Or create a Conda environment and activate it:

.. code-block:: shell

    $ conda create --name aidrin python=3.11
    $ conda activate aidrin

Install AIDRIn dependencies:

.. code-block:: shell

    $ pip install -e .

Run the application:

.. code-block:: shell

    $ flask --app aidrin run --debug

Open http://127.0.0.1:5000 in a browser.

PyPI
----------------

To use the PyPI package of AIDRIn, first install it:

Create a virtualenv and activate it:

.. code-block:: shell

    $ python3 -m venv .venv
    $ . .venv/bin/activate

Or on Windows cmd:

.. code-block:: shell

    $ py -3 -m venv .venv
    $ .venv\Scripts\activate.bat

Or create a Conda environment and activate it:

.. code-block:: shell

    $ conda create --name aidrin python=3.11
    $ conda activate aidrin

Install AIDRIn from PyPI:

.. code-block:: shell

    $ pip install -i https://test.pypi.org/simple/ aidrin==X

.. note::

    Where `X` is the latest version. For example:

    .. code-block:: shell

        $ pip install -i https://test.pypi.org/simple/ aidrin==0.6.4

