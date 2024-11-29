# Creation of EC2 instance for Lempstack server #
![EC2Lempstackserver](\IMAGES\EC2Lempstackserver.png "Creation of EC2 Instance for Lempstack server")

Step 3: Install MySQL Server
To install MySQL server, use the following command:
sudo apt install mysql-server
After installation, you can secure the MySQL installation by running:
sudo mysql_secure_installation
This will guide you through some important security settings for MySQL, like setting the root password.
Step 4: Install PHP and PHP-FPM
To install PHP along with PHP-FPM (FastCGI Process Manager for handling PHP requests with Nginx), you can install PHP along with some common extensions:
sudo apt install php-fpm php-mysql php-cli php-common php-curl php-xml php-mbstring




