# TransPro-Solver

##Overview
The TransProb Solver is a graphical user interface (GUI) application implemented in Python using the Tkinter library. It provides a convenient way to solve transportation problems using two different methods: Northwest Corner and Least Cost. The application takes user input for the number of sources, destinations, supplies, demands, and costs, and then calculates and displays the optimal allocations and total costs for both methods.

##Features
User-Friendly Interface: The application provides a clean and user-friendly interface to input transportation problem parameters.

Solver Methods: Supports two solution methods:
                                              - *Northwest Corner*
                                              - *Least Cost*

Results Display: The application displays the results in a scrolled text widget, showing the allocations matrix and total cost for each method.

Usage
Run the application by executing the script TransPro.py.

Input the required information:
                              - *Number of Sources*
                              Number of Destinations
                              Supplies (comma-separated)
                              Demands (comma-separated)
                              Costs (comma-separated, row-wise)
                              Click the "Solve" button to calculate and display the results.

##Dependencies
          - *Python 3.x*
          - *Tkinter library*

##Installation
Make sure you have Python installed on your system.

Clone this repository to your local machine : git clone https://github.com/your-username/TransPro.git

Change into the project directory : cd TransPro

Run the application : python TransPro.py
