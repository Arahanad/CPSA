# CPSA
1. Navigate to the Project Directory:

cd <CPSA>

2. Install Dependencies:

pip install beautifulsoup
pip install requests
pip install selenium
pip install undetected_chromedriver
pip install psutil
pip install mysql.connect


3. To scrape the site:

    steps:
    1.  get the listing of websie =>
            python main.py
        output file: listings.json

    2. get the data of listings =>
            python scap_data.py   
        output file: Output.json

    3. create a json data to csv file =>
            python json_helper.py
        output file: Final_Output.csv