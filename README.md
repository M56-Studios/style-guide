# TheCoupCompany Style Guide / Code Conventions

## PHP
We are following the common conventions:
* [PSR-1](http://www.php-fig.org/psr/psr-1/)
* [PSR-2](http://www.php-fig.org/psr/psr-2/)
* [PSR-4](http://www.php-fig.org/psr/psr-4/)

Exceptions:
* None

Params, properties and vars should be in camelCase, unless their origin is database call / ORM object.

We have no check for these in the built process (so far) but all developers are highly encouraged to follow those conventions to the best of their abilities.

Please set your IDE to use/check these code conventions: [PHPStorm / WebStorm](http://laraveldaily.com/how-to-configure-phpstorm-for-psr-2/)

## HTML
We are following this convention for HTML:
* [Google Style Guide for HTML](https://google.github.io/styleguide/htmlcssguide.html#HTML)

In depth information on valid HTML according to W3C:
* [HTML 5.1 W3C Recommendation](https://www.w3.org/TR/2016/REC-html51-20161101/)

Exceptions:
* Indenting lines with 4 instead of 2 spaces: As PHP's PSR-2 standard enforces indenting with 4 spaces, we decided on applying that to HTML as well. 

Please set your IDE to use/check these code conventions.

## JavaScript
For JavaScript there are multiple conventions, we decided on the following:
* [AirBnB JavaScript Code Conventions](https://github.com/airbnb/javascript)
* Inline JavaScript should follow [AirBnB JavaScript Code Conventions for ES5](https://github.com/airbnb/javascript/tree/es5-deprecated/es5)

Exceptions:
* ["func-names"](http://eslint.org/docs/rules/func-names): ["error", "never"],
* ["no-use-before-define"](http://eslint.org/docs/rules/no-use-before-define): ["error", { "functions": false }]
* ["no-underscore-dangle"](http://eslint.org/docs/rules/no-underscore-dangle): ["error", { "allowAfterThis": true }],
* ["comma-dangle"](http://eslint.org/docs/rules/comma-dangle): ["error", {
    "arrays": "only-multiline",
    "objects": "only-multiline",
    "imports": "only-multiline",
    "exports": "only-multiline",
    "functions": "only-multiline"
  }]

There is a prepared [.eslintrc file](https://github.com/TheCoupCompany/laravel-skeleton/blob/master/.eslintrc) in the root folder of the project.

Please set your IDE to use/check these code conventions.

### Prettier 
Prettier is an opinionated code formatter that helps us keeping a consistent code style in our company. We have a pre-commit hook set up (if you installed via vmconsole, if not please copy the file yourself to `.git/hooks/`) that will ensure that all commited JS/JSX files are run through [prettier/prettier](https://github.com/prettier/prettier). The [pre-commit](https://github.com/TheCoupCompany/style-guide/blob/master/pre-commit) is also part of this repo.

## CSS
We are following BEM conventions for CSS. 
Please check with Joel for further information.
