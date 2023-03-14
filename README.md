# magento24

Please install magento 2.4.5 latest version with sample data.
Take clone of this repository.
Run commands: php -dmemory_limit=6G bin/magento setup:upgrade && php -dmemory_limit=6G bin/magento setup:di:compile && php -dmemory_limit=6G bin/magento indexer:reindex && php -dmemory_limit=6G bin/magento s:s:d -f en_US && php -dmemory_limit=6G bin/magento c:f && php -dmemory_limit=6G bin/magento cache:clean
Run Project on local and go to PDP.
