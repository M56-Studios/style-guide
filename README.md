# TheCoupCompany Style Guide / Code Conventions

## PHP
We are following the common conventions:
* [PSR-1](http://www.php-fig.org/psr/psr-1/)
* [PSR-2](http://www.php-fig.org/psr/psr-2/)
* [PSR-4](http://www.php-fig.org/psr/psr-4/)

Exceptions:
* None

We have no check for these in the built process (so far) but all developers are highly encouraged to follow those conventions to the best of their abilities.

Please set your IDE to use/check these code conventions: [PHPStorm / WebStorm](http://laraveldaily.com/how-to-configure-phpstorm-for-psr-2/)

## HTML
We are following this convention for HTML:
* [Google Style Guide for HTML](https://google.github.io/styleguide/htmlcssguide.html#HTML)

Exceptions:
* Indenting lines with 4 instead of 2 spaces: As PHP's PSR-2 standard enforces indenting with 4 spaces, we decided on applying that to HTML as well. 

## JavaScript
For JavaScript there are multiple conventions, we decided on the following:
* [AirBnB JavaScript Code Conventions](https://github.com/airbnb/javascript)
* Inline JavaScript should follow [AirBnB JavaScript Code Conventions for ES5](https://github.com/airbnb/javascript/tree/es5-deprecated/es5)

Exceptions:
* "func-names": ["error", "never"],
* "no-use-before-define": ["error", { "functions": false }]

There is a prepared [.eslintrc file](https://github.com/TheCoupCompany/laravel-skeleton/blob/master/.eslintrc) in the root folder of the project.

We have no check for these in the built process (so far) but all developers are highly encouraged to follow those conventions to the best of their abilities.

Please set your IDE to use/check these code conventions.

## CSS
We are following BEM conventions for CSS. 
Please check with Joel for further information.
