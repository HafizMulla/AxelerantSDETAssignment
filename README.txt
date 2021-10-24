## Automation suite descriptions

My Automation Suite consist of the following files:

pageObject (folder) : This contain all the Page specific files created following POM model
-NavigateToPages.py: This file contains all the Methods for navigating to the different tabs and validating them. And it contain list-sourting method for selecting from the dropdown menu.
-NewsLetterPage.py: This file contains the newsletter subscription test case.

Resources (folder): This folder contain the Chromedriver.exe file which is used in the test case

testCases (folder): This folder contains all the test cases related to the following scenarios:
1)Navigate to multiple pages of the website and automate verification of header and footer.
	test_click_women_tshirts
	test_click_women_blouses
	test_click_women_casual_dresses
	test_click_women_evening_dresses
	test_click_women_summer_dresses
	test_click_dresses_casual_dresses
	test_click_evening_dresses
	test_click_summer_dresses
	test_click_tshirts_tab

2)Automate Newsletter subscription scenarios. The newsletter subscription is placed in the footer.
	test_newsletter_subscription

3)Automate Women > Dresses > Summer Dresses listing page. Note that filters and sorting options are broken on the site. Hence to verify filters and sorting, consider the default listing itself. (Tip - These two tests should obviously fail)
Consider the default listing and verify the results for any one of the filters.
	test_verify_listing_sorting

utilities (folder): This folder contain Utilities.py file which include the common method use in the test cases



## Installation:
Before running the test case, please install the following libraries in python/pycharm:
pip install selenium
pip install pytest
pip install 



## Execution
Please run the test_login.py file as this contains all the test cases
In pycharm, on top left side, Open the "edit configuration" and select the "test_login" file from the location "MyStoreCode2/testCases/test_login.py".
