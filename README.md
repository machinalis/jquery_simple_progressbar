jQuery Simple Progressbar
-------------------------

Super simple progressbar, from 0 to 100, as a jQuery plugin.

[Demo!](https://raw.githubusercontent.com/machinalis/jquery_simple_progressbar/master/example.html)

Usage
-----

Include the .js file, and then just do:

```javascript
    $('#an_element').simple_progressbar();
```

Or personalize your progressbar with options:

```javascript
    $('#an_element').simple_progressbar({'height': '50px', showValue: false, value: 75});
```

Available Options
-----------------


| Option                              | Description                                                                     |
| ----------------------------------- | ------------------------------------------------------------------------------- |
| value (no default value)            | progress value. If not providedit will use the text of the DOM element as value |
| normalColor (default "#76E29C")     | the color of the actual bar, when the progress is between 0 and 100             |
| overflowColor (default "#E67373")   | the color of the actual bar when the progress is above 100 ("ovefrlow")         |
| backgroundColor (default "#EEEEEE") | the color of the background behind the bar                                      |
| height (default '20px')             | the height of the full bar (background included)                                |
| width (default '200px')             | the width of the full bar (background included)                                 |
| internalPadding (default '1px')     | the spacing between the background and the actual bar                           |
| showValue (default true)            | true to show the value of the progress inside the bar                           |
| valueText (no default value)        | something to show inside the bar instead of the actual value                    |
