# Installing Python

Here is a [link](https://wiki.python.org/moin/BeginnersGuide/Download) to the official downloads page

We recommend to install Python 3.x (newer version) as it is fully compatible with Django and also supports some backward compatibilty with Python 2.

# PIP
__Do I need to install pip?__
pip is already installed if you are using Python 2 >=2.7.9 or Python 3 >=3.4 downloaded from python.org or if you are working in a Virtual Environment created by virtualenv or pyvenv. Just make sure to upgrade pip.

As we'll be using __virtualenv__ for our work, it would not be necessary to install __pip__ seperately. Installation would be required if you were to install Django without __virtualenv__.

__Installing with get-pip.py__
To install pip, securely download `get-pip.py` by following this link: [get-pip.py](https://bootstrap.pypa.io/get-pip.py). Alternatively, use curl:

`curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py`

Then run the following command in the folder where you have downloaded get-pip.py:

`python get-pip.py`

__Upgrading pip__

On Linux or macOS:

`pip install -U pip`

On Windows:

`python -m pip install -U pip`
