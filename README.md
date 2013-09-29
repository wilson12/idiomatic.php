# idiomatic.php

## Guidleines For Writing Consistent, Idiomatic PHP

* Tom Ellis [@tomgrohl](http://twitter.com/tomgrohl), [github](https://github.com/tomgrohl)

All code in any project should look like a single person typed it, no matter how many people contributed.

The following list outlines the practices that I use in all code that I am the original author of; contributions to projects that I have created should follow these guidelines.

I do not intend to impose my style preferences on other people's code or projects; if an existing common style exists, it should be respected.


## Table of Contents

 * [Whitespace](#whitespace)
 * [Beautiful Syntax](#spacing)
 * [Type Checking](#type)
 * [Conditional Evaluation](#cond)
 * [Practical Style](#practical)
 * [Naming](#naming)
 * [Misc](#misc)
 * [Native & Host Objects](#native)
 * [Comments](#comments)
 * [One Language Code](#language)


1. <a name="whitespace">Whitespace</a>
    - Never mix spaces and tabs.

2. <a name="spacing">Beautiful Syntax</a>

    A. Parens, Braces, Linebreaks

    ```php

    if (condition) {

    }

    if ( true ) {

    }
    else {

    }

    foreach (condition) {

    }

    for ($i = 0; $i < 100; $i++) {

    }

    while (condition) {

    }

    ```

    B. Assignments, Declarations, Functions/Methods, Classes


    ```php



    ```

3. <a name="type">Type Checking</a>

    A. Actual Types

    String:

    ```php
    is_string( $string )
    ```

    Integer:

    ```php
    is_int( 1 )
    ```

    Floating Point Number:

    ```php
    is_float( 1.2 )
    ```

    A Variable Considered Numeric:

    ```php
    is_numeric( $var )
    ```

    Array:

    ```php
    is_array( array(1,2,3) )
    ```

    Boolean:

    ```php
    is_bool( condition )
    ```

    Object:

    ```php
    $class = new Foo();
    is_object( $class )
    ```

    B. Coerced Types

    Consider the following as post data:

    ```php

    $post = array(
        'name' => 'Tom Ellis',
        'age'  => '24',
    );

4. <a name="cond">Conditional Evaluation</a>

5. <a name="practical">Practical Style</a>

6. <a name="naming">Naming</a>

7. <a name="misc">Misc</a>

8. <a name="native">Native & Host Objects</a>

9. <a name="comments">Comments</a>

10. <a name="language">One Language Code</a>
