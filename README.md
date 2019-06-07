# CS 269Q Final Project
## Matt Radzihovsky, Joey Murphy, Mason Swofford
Final Project Repository for CS 269Q, Spring 2019

# Installation instructions
After cloning this repository, users who already have a working installation of Anaconda can follow these steps to run the code:
1. Create a new conda environment
``conda create -n my_env``
2. Activate the environment
``source activate my_env``
3. Install pip
``conda install pip``
4. Install the repositories dependencies listed in the requirements.txt file
``pip install —user —requirement requirements.txt``
5. In another terminal window, enter the same virtual environment and initiate a QVM connection
``source activate my_env``
``qvm -S``
6. You’re now ready to run the code in the original window. See files for command line argument documentation.
``python quantum.py 3``
``python tsp_qaoa_updated.py 3 0.75 1``


