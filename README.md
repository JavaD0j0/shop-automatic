# ShopAutomatic

## Description

Are you tired of having to open up your browser and then type your desired shopping webpage? What about having to open different tabs of different sites
to search for the same item again multiple times?
If the answer is YES, then stop doing that and instead opt to use this automated application that does all that for you.

Just select the shopping webpage (or opt for all available sites) where you want to look for the item and also provide your username and 
password (optional) and then let the application automate all the steps to find you an available item.

<b>Enjoy!</b>

## Work in Progress

- Username and Password not fully implemented yet

    > I will be adding a database with pysql so when you enter your credentials, you can if you want, store your credentials in the DB for easier login next time, instead of using the YAML file.
- Only 3 sites are available right now. Will be implementing a few more later on...
- Find a way to bypass the recatcha required for EBAY to sign in...
- Figure out the best way to add items to shopping cart (either cheaper one or most popular item in the list, etc)

## Technologies

- PyQT for the GUI
- Python
- Selenium

## Set-Up

- In order for this to work you will have to download the web driver for the current Chrome version you have installed. At the time of writing this, I have version: `85.0.4183.121`
If you have a different Chrome version, download required web driver and place it in the resources folder after you have cloned the project.

- For now, create a YAML file where you can store your credentials in which the program will try to read from

```txt
1. Go to base directory: src\main\resources\base
- create a 'config.yaml' file in base folder with credentials to all sites so it automatically logins for you every time. A config.yaml file might already be there so just update with required information as needed.
```

## Installation

1. git clone https://github.com/JavaD0j0/shop-automatic
2. cd shopAutomatic
3. pip install -r requirements\windows.txt
4. run executable:
    - cd target
    - shopAutomaticSetup.exe
