# 2-Deoxy-Monosaccharide-Flow-Synthesis

Automation of Benzylated Rhamnal using Mechwolf

## Table of Contents

1. [Getting Started](#getting-started)
    1. [Automated Setup Script](#automatic)
    2. [Manual Setup for Windows](#manual-for-windows)
    3. [Manual Setup for MacOS](#manual-for-macos)
2. [JSON Files](#json-files)

### Getting Started

#### Automatic

NOTE: this script only works for MacOS for the time being. *In the future, we plan to make an automatic script for Windows as well*

Run `./setup` in order to install all binaries needed and python libraries. This script also generates a bash alias that allows you to automatically open up jupyter notebook if your terminal interpreter is bash.

#### Manual for Windows

1. Download Python 3

Navigate to this URL and follow this blog: https://phoenixnap.com/kb/how-to-install-python-3-windows (Note that you do not have to do the optional steps)

2. Verify Installation of Pip

Pip is a python package manager that allows you to download and manage python libraries with a single command. Verify that pip is installed properly by running `py -m pip --version` in the powershell application 

If the commands didn't work, try to manually download pip by following the documentation found here: https://pip.pypa.io/en/stable/installing/

3. Download all necessary Python Libraries

Run the following commands in order in the powershell:

* `py pip install mechwolf`
* `py pip install notebook`
* `py pip install graphviz`

#### Manual for MacOS

1. Download Homebrew

Run this command in the terminal: `curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh`

2. Download Python 3

Run the following two commands one after the other in the terminal:

* `brew install python3`
* `brew link python3`

2. Verify Installation of Pip

Pip is a python package manager that allows you to download and manage python libraries with a single command. Verify that pip is installed properly by running `python3 -m pip --version` in the terminal application

If the commands didn't work, try to manually download pip by following the documentation found here: https://pip.pypa.io/en/stable/installing/

3. Download all necessary Python Libraries

Run the following commands in order in the terminal:

* `pip3 install mechwolf`
* `pip3 install notebook`
* `pip3 install graphviz`
* `brew install graphviz`

### JSON Files
