# Steam Market History Exporter
The Steam Market History Exporter is a command line tool written completly in Python which allows you to extract your entire Steam Market History with all transaction (sale/purchase) in a reusable csv file. In addition a html file is generated automatically to view your transactions directly in the web browser.

## Features
+ Extract your **entire** Steam Market History
+ Creation of a reusable csv file with all transactions
+ Overview of all transactions represented user friendly in your web browser
+ Filtering of transcations via price, name and/or date of sale respectivly purchase
+ (*Coming soon:* Automatic calculation of the sum of the prices for the transactions selected)

## Requirements
+ **Python 3.8.X or higher:**
    + [Download Python 3.8.5](https://www.python.org/ftp/python/3.8.5/python-3.8.5.exe) (recommended)  
    + [All versions](https://www.python.org/downloads/)
+ **pip - The Python Package Installer:** (pip is already installed if you are using Python 3 >=3.4 downloaded from python.org)
    + Otherwise you can install pip by using the following [instructions](https://pip.pypa.io/en/stable/installing/)

## Installation & Usage
If you already installed **Python 3.8.X** or higher and **pip**  you are good to go. Otherwise you should check the requirements and install the software listed above.

### Usage:  
1. Download the entire repository by clicking *Download* and then choosing your desired archive format
2. Once downloaded you have to extract the entire folder to any desired location on your computer
3. After that start the tool by double-clicking the *run.<span></span>py* file
4. A command prompt should open which will guide you through the sequence of steps neccessary to fetch your data from Steam and convert the data into appropriate files.
5. After the tool is finished it will close itself and open a browser window for you to view your transactions

## Configuration
Currently there are not many configuration options available.
For now you can only customise the printed table via the *./libary/view.css* file. The table has the attribut *id="data"*

## Licence
![Creative Commons Attribution 4.0 International License](https://i.creativecommons.org/l/by/4.0/88x31.png "Creative Commons Licence")  
This work is licensed under a [Creative Commons Attribution 4.0 International License]("http://creativecommons.org/licenses/by/4.0/")