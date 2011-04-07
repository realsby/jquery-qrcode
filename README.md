# jQuery.qrcode.js

With jQuery.qrcode.js you can easily add qrcode to your webpages.
It is standalone, no external services which go on and off, or add latency
while loading. It is based on a <a href='http://www.d-project.com/qrcode/index.html'>library</a>
which build qrcode in various language. jQuery.qrcode.js wraps it to make it easy
to include in your own code.

Show, dont tell, here is a <a href='examples/demo.html'>demo</a>

## How to Use It

First include it in your webpage with the usual script tag
    
    <script type="text/javascript" src="jquery.qrcode.min.js"></script>

Then create a DOM element which gonna contains the generated qrcode image. Lets say
a div

    <div id="qrcode"></div>

Then you add the *qrcode* in this container by

    jQuery('#qrcode').qrcode("this plugin is great");

This is it. see it <a href='examples/basic.html'>live</a>.

## Conclusion

MicroEvent.js is available on github <a href='https://github.com/jeromeetienne/jquery-qrcode'>here</a>
under <a href='https://github.com/jeromeetienne/jquery-qrcode.js/blob/master/MIT-LICENSE.txt'>MIT license</a>.
If you hit bugs, fill issues on github.
Feel free to fork, modify and have fun with it :)