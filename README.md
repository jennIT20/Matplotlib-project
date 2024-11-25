Median Salary by Age: Python vs JavaScript Developers
This project analyzes the median salaries of Python developers, JavaScript developers, and all developers across different ages, using data visualization. The goal is to compare salary trends and see how different programming languages impact earnings as developers progress in their careers.

Project Overview
In this project, a line graph is created using the matplotlib library to visualize the median salary (in USD) of developers based on their age. The data includes salary information for:

Python Developers
JavaScript Developers
All Developers
The graph displays how the median salary changes with age and how the salaries of Python and JavaScript developers compare to those of all developers.

Features
Visualizes median salaries of developers based on age.
Compares salary trends for Python and JavaScript developers.
Uses Python and matplotlib to generate a line graph for easy comparison.
Saves the plot as a PNG image (plot.png).
Installation
Clone this repository:

bash
Copy code
git clone https://github.com/YOUR_USERNAME/median-salary-by-age.git
cd median-salary-by-age
Install the required Python libraries:

bash
Copy code
pip install matplotlib
Usage
Run the script:

bash
Copy code
python plot_salary_by_age.py
The script will generate a plot and display it using matplotlib. It will also save the plot as plot.png in the current directory.

Example Output
The graph will display the following:

X-axis: Age of developers (18-55).
Y-axis: Median salary in USD.
Line 1: Median salary of Python developers.
Line 2: Median salary of JavaScript developers.
Line 3: Median salary of all developers (shown in dashed line).
Code Explanation
Data Arrays: The project includes three lists (py_dev_y, js_dev_y, dev_y), which contain the median salary data for Python, JavaScript, and all developers respectively.
Plotting: matplotlib is used to plot the data, adding labels, titles, and a legend for clarity.
Contributing
If you would like to contribute to this project, feel free to fork the repository and create a pull request. For any issues, please open an issue on GitHub.

License
This project is licensed under the MIT License - see the LICENSE file for details.

