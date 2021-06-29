<h1>How to setup magento 2.3.5-p2</h1>
<p>
<li>Run composer install</li>
<li>Get magento authentication key and enter when prompted</li>
<li>Run composer update</li>
</p>
<h3>Install using web wizard</h3>
<p><li>Browse the url from browser and follow the steps</li></p>
<h3>Install using CLI</h3>
<p>Use the below command, change as per your requirement and run in magento root directory <br/>
bin/magento setup:install \
--base-url=http://www.yourshopdomain.com/ \
--db-host=localhost \
--db-name=magento2 \
--db-user=shopdbuser \
--db-password=shopDBuser_123 \
--admin-firstname=admin \
--admin-lastname=admin \
--admin-email=admin@admin.com \
--admin-user=admin \
--admin-password=admin123 \
--language=en_US \
--use-rewrites=1
</p>