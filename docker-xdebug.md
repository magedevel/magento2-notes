To run xdebug with console use this command:

 docker-compose exec -e XDEBUG_CONFIG="idekey=phpstorm" -e PHP_IDE_CONFIG="serverName=magento2" magento bin/magento the:command
 magento2 is the configuration on your php storm.
