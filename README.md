1. Download lasted version of composer

curl -sS https://getcomposer.org/installer | php

2. Move Composer to local/bin
sudo mv composer.phar /usr/local/bin/

3. Edit your .bash-profile
nano ~/.bash_profile

4. Make composer short command by adding this to the end of the file
alias composer="php /usr/local/bin/composer.phar"

Exit and Save 

Restart Terminal 
