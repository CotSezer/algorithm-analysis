# Array Processing Time Analysis

## Overview

This program implements a parallel machine processing simulation using MPI4py. It simulates the processing of products through a network of machines, each performing specific operations. The code is designed to run in a parallelized environment using MPI for efficient parallel processing.

## Requirements
- Python 3.x
- MPI4py library


## How to Run

1. Ensure Python is installed on your system.
2. Firstly `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"` writing this to the terminal, install Homebrew
3. Then `brew install python`
4. Then `brew install open-mpi`
5. After that, `pip3 install mpi4py`
6. Run the script using the command in the file path: `mpiexec -n <number_of_processes> python your_code.py input.txt output.txt`
7. If it is oversubscribe: `mpiexec --oversubscribe -n <NUMBER> python3 test.py test_input.txt output.txt`. NUMBER refers to number of machine + 1 you will use.



Feel free to explore and adapt this script for your specific use cases and performance analysis needs.

Happy coding!



