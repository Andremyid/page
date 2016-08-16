# page
The Andremyid Page package.

## Installation

* Add the following to your `Composer JSON` file
```
"andremyid/page": "~0.0"
```
* Run Composer
```
$ composer update
```
* Add the following to 'Andremyid/Framework-Core' => 'ServiceProvider'
```
Andremyid\Page\PageServiceProvider
```
* Run the migration

You can use database from WordPress, or copy from sample database migrate manually (you can modify as you like of the sample)
```
// first, optional
$ composer dump-autoload
// and then
$ php andre migrate
```
## Usage

### Extending
