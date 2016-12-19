# sagawa
codeigniter3 RestAPI-Server

## install 
composer install

## 設定ファイル

development/config.php
<code>
$config['base_url'] = 'https://{host}/';
</code>

development/rest.php
<code>
$route['users/test']['GET'] = 'users/index';
</code>


development/routes.php
<code>
$route['users/test']['GET'] = 'users/index';
</code>


## 動作検証
'curl -X GET -H "Accept: application/json" https://{host}/users/test?type=json'

