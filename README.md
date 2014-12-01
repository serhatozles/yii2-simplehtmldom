Simple HTML Dom
===============
Simple HTML Dom

Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require --prefer-dist serhatozles/yii2-simplehtmldom "dev-master"
```

or add

```
"serhatozles/yii2-simplehtmldom": "dev-master"
```

to the require section of your `composer.json` file.


Usage
-----

Once the extension is installed, simply use it in your code by  :

```php
<?= \serhatozles\simplehtmldom\SimpleHTMLDom::file_get_html('http://google.com'); ?>```

See more: http://simplehtmldom.sourceforge.net/