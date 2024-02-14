# ESC_1B_ESB
Jupyter notebooks for ESB course


The practicals in this course will be in jupyter notebook, which combines code and narrative text on a web-based interactive platform. All the code is in Python, and make use of various Python libraries. The practicals are hosted on GitHub, a code-hosting platform, allowing for version control and collaboration.

Step 1: Installing Anaconda

Anaconda helps distribute software packages across different platforms. Follow the instructions for installation for your specific platform here. This already installs Python and Jupyter Notebook. Anaconda has a graphical interface to install packages, this document will however give command line comments.

Step 2: Install required packages

In a terminal install the following packages (note if you are a regular anaconda user, you might want to set up a new environment, so packages don’t interfere:

Install git to access github:

conda install -c anaconda git

Install ObsPy

conda install -c conda-forge obspy

Step 3: Set up git repository

- Make a directory in which you want the practicals.
- Go into this directory
- Type: git init
- Type: git clone https://github.com/sannecottaar/ESC_1B_ESB.git
- A directory full of practicals should have appeared!

Step 4: Open a practical

- Go into ESC_1B_ESB/Pract_41
- Now run jupyter notebook body_wave_predictions.ipynb
- You are ready! Individual code blocks can be run with shift+enter

