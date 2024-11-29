 # Step 6: Verify the Installation

# To check if everything is working properly:
# Create a PHP info file to test PHP processing:
'sudo nano /var/www/html/info.php'

# Add the following code to the info.php file:
' <?php
phpinfo();
?> '

 # Visit http://your_server_ip/info.php in your browser. You should see the PHP information page, confirming that Nginx is processing PHP requests.
 ![PHP_information_page](\IMAGES\PHP_information_page.png "PHP INFORMATION PAGE")
 
