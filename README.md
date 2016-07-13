Magento 2 Russian Language Package

Installation

*** Downloading Module with Composer ***
composer require atopt/m2-language-ru_ru:*

*** Installing Module with Magento Command Line Tool ***
./bin/magento module:enable atopt/m2-language-ru_ru
./bin/magento setup:upgrade
./bin/magento cache:clean
rm -rf var/view_preprocessed/ pub/static/

*** Configuration ***
Admin > Stores > Configuration > Advanced > Advanced enable m2-language-ru_ru
