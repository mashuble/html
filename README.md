# html
# HTML Helpers For Laravel 5.2

To install:
composer require mashuble/html

In app/config.php in the array of providers
Illuminate\Html\HtmlServiceProvider::class,

In app/config.php in the array aliases
'Form' => Mashuble\Html\FormFacade::class,
'HTML' => Mashuble\Html\HtmlFacade::class,
