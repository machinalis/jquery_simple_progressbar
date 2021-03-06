jQuery Simple Progressbar
-------------------------

Super simple progressbar, from 0 to 100, as a jQuery plugin.

[Demo!](https://rawgit.com/machinalis/jquery_simple_progressbar/master/demo.html)

Usage
-----

Include the .js file, and then just do:

```javascript
    $('#an_element').simple_progressbar();
```

Or personalize your progressbar with options:

```javascript
    $('#an_element').simple_progressbar({'height': '50px', value: 75});
```

Available Options
-----------------


| Option                              | Description                                                                     |
| ----------------------------------- | ------------------------------------------------------------------------------- |
| value (no default value)            | progress value. If not provided it will use the text of the DOM element as value|
| normalColor (default "#76E29C")     | the color of the actual bar, when the progress is between 0 and 100             |
| overflowColor (default "#E67373")   | the color of the actual bar when the progress is above 100 ("ovefrlow")         |
| backgroundColor (default "#EEEEEE") | the color of the background behind the bar                                      |
| height (default '20px')             | the height of the bar (no background included)                                  |
| width (default '200px')             | the width of the bar (no background included)                                   |
| internalPadding (default '1px')     | the spacing between the background and the actual bar                           |
| showValue (default false)           | true to show the value of the progress inside the bar                           |
| valueText (no default value)        | something to show inside the bar instead of the actual value                    |

And worth mentioning, you can style the text of the values using css, just point to the container selector.
