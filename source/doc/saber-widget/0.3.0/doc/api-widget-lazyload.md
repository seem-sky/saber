layout: doc
comments: false
date: 2014-10-2 10:39:9
repo: saber-widget
ref: 0.3.0
---

# LazyLoad

懒加载控件。


## Usage

``` javascript
var widget = require( 'saber-widget' );
require( 'saber-widget/LazyLoad' );

var lazyload = widget.lazyload();

lazyload.on( 'load', function ( ev, node ) {
    console.info( 'load', node );
});

lazyload.on( 'complete', function () {
    console.info( 'complete' );
});
```

## API

TODO

