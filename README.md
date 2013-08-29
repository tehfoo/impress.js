# impress.js with substeps and extra shortcut keys!

This is a fork of [impress.js][1] and [impress.js with substeps][2] that adds extra shortcut keys. For documentation on everything else about impress.js, read that [documentation][1] and the [substeps documentation][2].

## Added functionality
* Shortcut (`ESC`) to natigate to overview.
* Navigate backwards with `backspace`.
* Toggle blank screen with `.`. (This is a standard PowerPoint shortcut and some presentation tools, such as my [Logitech Wireless Presenter][3], have a special key for it.)
* Last substep gets deactivated when navigating to next step.

## How to use
* Press `ESC` in a presentation as a shortcut to go to the overview. Make sure you have a `step`-element with the id `overview` in your HTML, e.g.

```html
    <div id="overview" class="step" data-x="-2000" data-y="5000" data-scale="15">
    </div>
```
    
* In any presentation, you can now also use `backspace` to navigate backwards.
* In any presentation, press `.` to toggle blank screen.

## LICENSE

Same as [impress.js][1], this code is released under the MIT and GPL Licenses.


[1]: https://github.com/bartaz/impress.js
[2]: https://github.com/tehfoo/impress.js
[3]: http://www.logitech.com/nl-nl/support/175?crid=402
