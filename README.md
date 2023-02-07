
# Remove PHP in linux
-----------------

    $ sudo apt-get purge php8.*
    $ sudo apt-get autoclean
    $ sudo apt-get autoremove

# Install PHP in linux
-----------

    $ sudo apt update && apt upgrade -y
    $ sudo add-apt-repository ppa:ondrej/php
    $ sudo apt update
    $ sudo apt install php8.2 -y
    $ php --version
    $ sudo apt-get install -y php8.2-cli php8.2-common php8.2-fpm php8.2-mysql php8.2-zip php8.2-gd php8.2-mbstring php8.2-curl php8.2-xml php8.2-bcmath
    $ php -m


# Install Symfony CLI
----------------
    $ wget https://get.symfony.com/cli/installer -O - | bash
    $ curl -sS https://get.symfony.com/cli/installer | bash

# Install Symfony
------------------

    symfony new symfony --version="5.4.*" --webapp
