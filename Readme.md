# Sales Analysis
step 1:
Basically, this project was to first;
generate a dataframe from a dictionary

step 2:
Calculate the Total Profit for each product using the formula - net_revenue_per_product = (retail_price - wholesale price) * sales

STEP 3: Determine the following;
How much total net revenue you received from all of these sales?
What product is product retail price more than twice the wholesale price?
How much did the store make from food vs. computers vs. books?
Because your store is doing so well, you’re able to negotiate a 30% discount on the wholesale price of goods. Calculate the new net revenue.

Setup
Install the required packages to be able to run the evaluation locally.

You need to have Python 3 on your system (a Python version lower than 3.10). Then you can clone this repo and being at the repo's root :: repository_name> ... follow the steps below:

Windows (Python should be added to the Path variable of environment):

  python3 -m venv venv; venv\Scripts\activate; python -m pip install --upgrade pip; python -m pip install -r requirements.txt  

Linux & MacOs:

  python3 -m venv venv; source venv/bin/activate; python -m pip install --upgrade pip; python -m pip install -r requirements.txt

  The both long command-lines have a same structure, they pipe multiple commands using the symbol ; but you may manually execute them one after another.

1.Create the Python's virtual environment that isolates the required libraries of the project to avoid conflicts;

2.Activate the Python's virtual environment so that the Python kernel & libraries will be those of the isolated environment;

3.Upgrade Pip, the installed libraries/packages manager to have the up-to-date version that will work correctly;

4.Install the required libraries/packages listed in the requirements.txt file so that it will be allow to import them into the python's scripts and notebooks without any issue.

Evaluation
This evaluation will be automatically grade, so please follow the instructions carefully.

You can run this command bellow being at the root of the repository to be sure your solutions are the good ones before to push your solutions.

python -m pytest -v

If everything is okay, you will have such an output

================================================= test session starts =================================================
platform xxx -- Python 3.9.6, pytest-7.2.0, pluggy-1.0.0 -- /xxx/python3
cachedir: .pytest_cache
rootdir: xxx/Git-and-GitHub-final-assignment
collected 3 items                                                                                                     

tests/test_filled_table.py::test_not_empty_table PASSED                                                         [ 33%]
tests/test_filled_table.py::test_not_empty_rows PASSED                                                          [ 66%]
tests/test_readme_table.py::test_contains_table PASSED                                                          [100%]
