# Step 1: Update Package Index #
# Before installing anything, it's a good practice to update your package list to ensure you're installing the latest versions available from the repository. #
'sudo apt update'
![server update](\IMAGES\server_update.png "Installation of latest updates")

# Step 2: Install Nginx #
# To install Nginx, run the following command: #
'sudo apt install nginx'
# Once installed, you can start and enable Nginx to run on boot:#
' sudo systemctl start nginx '
'sudo systemctl enable nginx'
![installing_nginx](\IMAGES\server_update.png "nginx Server Installation")
