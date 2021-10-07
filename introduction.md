# Python packages
To understand packages, we can think of them as software. Each package is a software developed for specific functions, for example the pandas package enables users to deal with table-like data (such as excel files), and the matplotlib package is focused on graphs. In reality, a package is simply a collection of modules that contain executable files and functions.
To use a package, we need to:
1. Install it in our computer.
2. Import it on the script/notebook we are working. 

For package installation, it is very convenient to work with virtual environments (venv). We can install different packages or package versions in several venvs, thus preventing conflicts between them. For example, if one project is using pandas version 1.0 and another is using pandas version 1.3, we might want to have one environment with pandas v1.0 installed and another with pandas v1.3, as some functions might differ between versions and thus mess our scripts.
We will install packages as we need them throughout the course.

# Conda environments
Conda is a package manager that creates virtual environments on Windows, macOS and Linux, and is the venv management system that we will use throughout the course.
To use it, we need first to install Anaconda --> <https://www.anaconda.com/products/individual>

# Before the course starts
Please download and install Anaconda in the computer you will use during the course:
1. Choose the right installation package for your system (Windows, Linux or macOS) and processor (64 or 34 bit). Most computers nowadays run on a 64-bit processor, but if you are unsure, type System Information on the computer search bar and check the System Type (x64 or x34).
2. Open the executable file and follow the set up wizard.
3. Accept the License Agreement (Anaconda is a free, open source package)
4. Install just for your user (if its a shared computer) or all users if its your personal computer
5. Choose the installation folder (you can simply leave the default option)
6. (For Windows users): tick both Advanced Options (Add Anaconda to my PATH environment variable / register Anaconda as my default Python 3.8). Even if it says Not       Recommended, we will explain during the course.

You do not need to do anything else, we will explore Anaconda and venvs in the first lesson, so do not worry if the concepts above are a bit complicated to follow, you will quickly understand them when we start working.
