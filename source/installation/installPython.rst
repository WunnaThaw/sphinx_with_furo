Installing Python
====================


To begin using Sphinx and creating `.rst` documentation, you need to have Python installed on your system. Follow the steps below to install Python on your machine.

1. Download Python  
--------------------

Visit the official Python website:

https://www.python.org/downloads/

Choose the appropriate version for your operating system (Windows, macOS, or Linux).


2. Install Python
----------------------

After downloading the installer, run it and follow the instructions for your operating system.

- Windows:  
    - Run the `.exe` installer.
    - Make sure to check the box **"Add Python.exe to PATH"** before proceeding with the installation.
    - Choose "Install Now" or customize your installation settings.

1.Click Install Now button

    .. image:: img/install1.png

    .. image:: img/install2.png

2.Installation is finished. Click the Close button.

    .. image:: img/install3.png

- macOS:  
    - Run the downloaded `.pkg` file and follow the on-screen instructions.
    - Python will be installed in `/usr/local/bin/python3`.

- Linux:  
    - Python may already be installed on most distributions. If not, use the following commands to install:
    - Debian/Ubuntu-based systems:
    
    ::
    
        > sudo apt update
        > sudo apt install python3 python3-pip
    
    - Red Hat/Fedora-based systems:
    
    ::
    
        > sudo dnf install python3 python3-pip

3. Verify Installation  
------------------------

After installation, you can verify that Python is correctly installed by checking the version in your terminal or command prompt.

Open your terminal or command prompt and type:

::

    > python --version

or for Python 3 specifically:

::

    > python3 --version

You should see something like:

::

    > Python 3.x.x


4. Upgrade pip (Optional but recommended)  
------------------------------------------

After installing Python, ensure that **pip** (Python's package manager) is up to date. Run the following command:

::

    > python -m pip install --upgrade pip

Once Python is installed, you're ready to start using Sphinx and other Python tools!



