# client-sdk-squad2



Squad2 client side sdk to send events to REST API squad

To install this project:

1) composer install 

2) mv config.example config.php

3) set the environment vars in config.php (email,password and ambiente of your monitored application)
Example:
const MAIL = "teste@teste.com";
const PW = "12345678";
const ENV = "dev"; #["dev", "produção", "homologação']

4) php client_sdk.php


