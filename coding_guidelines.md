# Coding Guidelines #

* Use single and double quotes when appropriate. If you're not evaluating anything in the string, use single quotes.
* Use tabs and not spaces, as this allows the most flexibility across clients.
* Braces should be used for multiline blocks in the style shown here:
```php

    if ( condition ) {
    action1();
    } elseif ( condition2 && condition3 ) {
        action3();
    } else {
        defaultaction();
    }

```
* Don't close php "?>""
* Remove trailing spaces at the end of each line of code.
* Naming Conventions. 
    Method names: model_verb_object, model_returns_value
    Var names: use model name/controller name_nature_of_variable e.g: user_admin_flag, user_fullname, user_requires_more_permissions
    [Clarity over brevity in variable and method names](http://37signals.com/svn/posts/3250-clarity-over-brevity-in-variable-and-method-names)

* Use Ternary operators when working with single if else fall.


Above is to start with will update this as we move on.