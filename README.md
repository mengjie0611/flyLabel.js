# flyLabel.js - [DEMO](http://athaeryn.github.com/flyLabel.js)

### _Your labels wish they were this fly_

Inspired by [Matt Smith's float label
concept](http://mattdsmith.com/float-label-pattern/).

It's not the goal of this plugin to look like the FloatLabel concept.
In fact, the goal is not to look like anything at all. The style,
transitions, and animations are all determined by CSS. There are several
examples in the [demo](http://athaeryn.github.io/flyLabel.js).

## Get it

You'll probably want to download the minified version in `dist/`.

        $ curl -O https://raw.github.com/athaeryn/flyLabel.js/dev/dist/flyLabel.min.js

## Use it

This snippet from the demo is pretty self-explanatory:

``` html
<script src="/demo/vendor/jquery.min.js"></script>
<script src="/dist/flyLabel.min.js"></script>
<script>
  if (Modernizr.input.placeholder) {
    $('body').flyLabels();
  }
</script>
```

Of course, a little more explanation can't hurt, right? You can call
`flyLabels()` on a container element, and all the elements with class
`.fly-group` will be automagically made awesome. I'm going to get around to
writing more thorough documentation on this soon, but the demo should be helpful for
now.

## Thank You

These people were tremendously helpful in the creation of this plugin:

- [audionerd](https://github.com/audionerd)
- [wfendler](https://github.com/wfendler)
- [mckennedy](https://github.com/mckennedy)
- [tjdunklee](https://github.com/tjdunklee)
