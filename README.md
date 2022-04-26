# SC-RCT
Final Project for DSCI 551
App Deployed at https://share.streamlit.io/harvey-fin/sc-rct/main/main.py

If running the App on Your Localhost:
------------------------------------
package & software installations:

UPDATE: The requirements.txt is added to the repository

install a chromedriver under the same folder as web_scrapper.py
for more information about chromedriver, visit https://chromedriver.chromium.org/downloads

MAKE SURE that the chromedriver is compliant with the version of your chrome browser.

Python Streamlit:
```
pip install streamlit
```
I am using the streamlit version 1.8.1

Python Selenium Package:
```
pip install selenium
```
Other packages that is commonly used: pandas, requests, datetime

Error Handling:
-----------------------------------
There could be module conflict with the click module due to updates of the click package.
In short, ```AttributeError: module 'click' has no attribute 'get_os_args'``` occured because click.get_os_args deprecated on module ```click 8.1.0```
the way to handle this is more clearly explained in this link: https://github.com/streamlit/streamlit/issues/4555

If you don't encounter such problem of using Streamlit, please neglect the content above

Errors related with web-scraping
It is important that you enter the course ID in correct format: 'ABCD123', and the correct professor name that can be searched on https://uscdirectory.usc.edu/web/directory/faculty-staff/

It is possible that you might encounter some error during webscrapping, it might be because of the network connection speed. Please consider refreshing the page and do it again!

How to compile the code in terminal:
------------------------------------

in terminal, do
```
streamlit run #path to main.py
```
for example, I would run
```
streamlit run /Users/harveyfu/Desktop/pythonProject/DSCI551/Group_Project/main.py
```
in my terminal

Notice that you could not directly run ```python main.py```, or any of the py files. Otherwise, you may get the error message of ```AttributeError: module 'click' has no attribute 'get_os_args'``` as mentioned above. The solution is explained in previous section.

