# selenium + MAC OS + Python


## Q1 Error code like this：
selenium.common.exceptions.WebDriverException: Message: 'geckodriver' executable needs to be in PATH.

### reason：
driver for browser knerl uninstall or  install incorrect. If you choose Mozilla firefox , you should download geckodriver

### solution of mine:
download browser knerl driver, unzip it and move to directory /usr/local/bin/  ,then rerun your script


## Q2 Error code: KeyError: 'sessionId'

### reason:
version of selenium not correct

### solution of mine: 
update selenium with command "pip install -U selenium" or "sudo pip install -U selenium"