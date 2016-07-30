# animate-easing
##easing

**Link:**    [All easing](http://easings.net/zh-cn#)

###Template:
```
$('#myDiv').animate(
    { opacity: 0 }, // what we are animating
    {
        duration: 'fast', // how fast we are animating
        easing: 'swing', // the type of easing
        complete: function() { // the callback
            alert('done');
        }
    });
```
