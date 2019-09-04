monex grid
==========
grid view for monex

Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require --prefer-dist ahyo/monexgrid "*"
```

or add

```
"ahyo/monexgrid": "*"
```

to the require section of your `composer.json` file.


Usage
-----

Once the extension is installed, simply use it in your code by  :

```php
<?= \ahyo\monexgrid\MonexGrid::widget(); ?>```