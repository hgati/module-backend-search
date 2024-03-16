# Magento2 Backend Search
- This module searches through Magento's default backend search, incorporating items from the configuration / menu as well.

## Installation
- Install the module composer by running `composer require hgati/module-backend-search:dev-master`
- enable the module by running `php bin/magento module:enable Hgati_BackendSearch`
- apply database updates by running `php bin/magento setup:upgrade`
- Flush the cache by running `php bin/magento cache:flush`

