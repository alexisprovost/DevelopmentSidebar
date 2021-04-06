# DevelopmentSidebar

Development sidebar that displays information related to the server you are visiting.

# Installation

The bar can be added in the .htaccess file or in you PHP application.

## .htaccess
```htaccess
php_value auto_append_file "/DevelopmentSidebar/index.php"
```

## PHP
```PHP
include $_SERVER['DOCUMENT_ROOT'].'/DevelopmentSidebar/index.php';
```

# Sidebar styles
<img src="https://img.sshort.net/i/LqJ3.png">
