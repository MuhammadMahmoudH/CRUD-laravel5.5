#CURD Example

## Operations
* Create new record with php blade 
* Read and request data
* update
* Delete

### installation and setup
* run: npm install 
* composer require laravelcollective/html
```$xslt
'providers' => [
	....
	Collective\Html\HtmlServiceProvider::class,
],
'aliases' [
	....
	'Form' => Collective\Html\FormFacade::class,
    'Html' => Collective\Html\HtmlFacade::class,
],
```
* create mySQL Database and edit .env File
```$xslt

DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=here your database name(blog)
DB_USERNAME=here database username(root)
DB_PASSWORD=here database password(root)

```
* run: php artisan migrate

### Thanks 
Muhammad Mahmoud