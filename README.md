yii2-yandex-metrika
===================

Yii2 widget to add Yandex.Metrika counter on page
Forked from dkushnikov/yii2-yandex-metrika


Installation
------------
The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require "p0vidl0/yii2-yandex-metrika" "*"
```

or add

```json
"p0vidl0/yii2-yandex-metrika" : "*"
```

to the require section of your application's `composer.json` file.

Usage
-----
```php
use yii\widgets\YandexMetrikaCounter;

<?= YandexMetrikaCounter::widget(
    [
        'counterId' => 12345,
    ]
) ?>
```
