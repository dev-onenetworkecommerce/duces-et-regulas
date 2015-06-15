#PHP Conventions

- Each Space (4 spaces, **No Tabs**)
- Beautiful Syntax
    - Cases
        ```php
            $do_not_do_snake_cases;
            even_in_functions();

            \\Classes should always be in pascal Case
            class ModelOne {

            }

            \\All initialization of variables should be on the top

        ```
    - Parens, Braces, Linebreaks
        ```php
            //if, else, for, while, do, try (any non-function codeblock) should have a space before and between
            //Do
            if ($variable) {

            } else {

            }

            //Do Not

            if ($variable)
            {

            }
            else
            {
                //we must enforce simplistic readability
            }

            //Do Not do shorthand methods
            if ($variable)
                //some codebase
            else
                //here

        ```

    - Asignments, Declarations, Functions
        ```php

            function opening curly-brace should be on a new line break

            //Do
            function x()
            {

            }

            //Do Not

            function createCodeLikeThis() {

            }

            //old style of array is A DO NOT
            $doNot = array (
                'some array'
            );

            $do = ['some array'];


        ```

- Type Checking, should be forced
    ```php
        $x === 0
    ```

- Do not forget to use single quotes
    ```php
        $x = "This takes too much server to load";
        $y = 'while this does not require any';
    ```


#Supports and Requirements
 - [PSR 0(Autoloading)](http://www.php-fig.org/psr/psr-0/)
 - [PSR 1(Basic Coding Standsards)](http://www.php-fig.org/psr/psr-1/)
 - [PSR 2(Advanced Coding Guide)](http://www.php-fig.org/psr/psr-2/)
 - [PSR 3(Logging, and interfacing)](http://www.php-fig.org/psr/psr-3/)
 - [PSR 4(Improved Autoloading)](http://www.php-fig.org/psr/psr-4/)

 #Sublime package to install
 - [PHP Formatter to PSR2](https://packagecontrol.io/packages/phpfmt) Install with `package control`
