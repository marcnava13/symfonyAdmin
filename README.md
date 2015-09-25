Administrator Symfony
=====================

This repository is an administrator made with Symfony2. It is based on integration with FOSUserBundle SonataAdminBundle.

## How to install this administrator?

#### Requirements:
* Having Composer installed on your operating system. If you do not know how you can install it on this [link].
* Having created in MySQL, Mongo or other database administrator, our database. 

### Installation
```sh
$ git clone https://github.com/marcnava13/symfonyadmin.git <folder>
$ composer install
$ php app/console doctrine:schema:update --force
$ php app/console fos:user:create <username> <email> <password> --super-admin
```

### Development

Execute the following command from the console to launch our application in a browser to view it.

```sh
$ php app/console server:run
```

For questions count me in [www.marcosnavarro.net]

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does it's job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)

[link]: <https://getcomposer.org/>
[www.marcosnavarro.net]: <http://www.marcosnavarro.net>