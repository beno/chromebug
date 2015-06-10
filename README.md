#Chrome Bug

This is a simple demo of a strange bug I encountered when minifying with steal-tools.

- clone the project
- run 'npm install'
- minify with 'node build.js'
- start a webserver, eg. 'ruby -run -ehttpd . -p8000'

On a Mac, use Chrome/Chromium to visit

* localhost:8000/index.dev.html => page says 'Hello'
* localhost:8000/index.html => page says nothing (???)

On Safari, both pages say Hello.
