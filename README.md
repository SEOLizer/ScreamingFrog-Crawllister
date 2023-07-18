# ScreamingFrog-Crawllister
Script that supports you to create a list of crawls without the ScreamingFrog and to create the required JDBC connection string to a crawl in order to be able to access the Derby database directly with SQL.

# SEOLizer
The code is provided to you by [SEOLizer](https://www.seolizer.de).

## Installation
- Install PHP on your system
  - MAC:
    - Install Homebrew "/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
    - Install PHP with "brew install php"
- clone this repository "clone https://github.com/SEOLizer/ScreamingFrog-Crawllister.git"

## Require
This library based on PHP (https://www.php.net/).

## Filelist
- listCrawls.php (Script with mainfunction)

## Use the Script
- Open a terminal and enter the following command "php listCrawls.php"
- As an output you get a list of the crawls in your ScreamingFrog
- The script is now waiting for your input. Enter the number in front of your desired crawl and press enter.
- The script then returns the data from the crawl.
