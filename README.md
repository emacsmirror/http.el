## http.el
*An HTTP client for Emacs -*- lexical-binding: t -*-*

---
[![Travis build status](https://travis-ci.org/emacs-pe/http.el.png?branch=master)](https://travis-ci.org/emacs-pe/http.el)

`http.el` provides an easy way to interact with the HTTP protocol.

### Examples

![http.el screenshot](misc/screenshot.png)

See: [misc/example.txt](misc/example.txt)

### TODO

+ [ ] Add code block support for org-mode

### Related projects

+ [httprepl.el](https://github.com/gregsexton/httprepl.el): An HTTP REPL for Emacs.
+ [restclient.el](https://github.com/pashky/restclient.el): HTTP REST client tool for Emacs.

### Function Documentation


#### `(http-query-alist QUERY)`

Return an alist of QUERY string.

#### `(http-parse-headers START END)`

Return the parsed http headers from START to END point.

#### `(http-capture-headers-and-body START END)`

Return a list of the form `(header body)` with the captured valued from START to END point.

#### `(http-end-parameters &optional START)`

Locate the end of request body from START point.

#### `(http-process)`

Process a http request.

-----
<div style="padding-top:15px;color: #d0d0d0;">
Markdown README file generated by
<a href="https://github.com/mgalgs/make-readme-markdown">make-readme-markdown.el</a>
</div>
