# sagawa
codeigniter3 RestAPI-Server

## install 

composer install

## settings

development/config.php
### update
$config['base_url'] = 'https://{host}/';


development/rest.php
### add


development/routes.php

### add
$route['users/test']['GET'] = 'users/index';


## sample
''curl -X GET -H "Accept: application/json" https://{host}/users/test?type=json''

