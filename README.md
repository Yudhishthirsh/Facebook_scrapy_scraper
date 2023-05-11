# Facebook_scrapy_scraper

Download pycharm and setup virtual enviroment in your pycharm using Command in terminal below.
pip install virtualenv
or
can follow the below link to create virtual Environment.
https://www.jetbrains.com/help/pycharm/creating-virtual-environment.html#env-requirements

After creating virtual invironment in your project.
1) Install all the python packadges as mentioned in requirments.txt
2) pip install r-requirments.txt
Now all the required packdges get installed inside your project.

To scrape data from public groups you need a facebook login.
1) Need to add your credentials in parameter.py file.

Now Go to the quotes(outer) directory using command in terminal mentined below
1) cd .\quotes\

After reashing to the quotes directory
1) Run following command in terminal.
2) scrapy crawl result21 -o Output.csv --nolog in the terminal. Where Output.csv is the file name in which the output will be recorded. 

Then run command mentioned below in case any error : no module found "Parameter"
 $env:PYTHONPATH = "C:path of the parameter file;$env:PYTHONPATH"
 
 
