Golang version of the Koalab API
================================

Koalab is an internal project of af83, soon to be released as Open-Source.
It works with a Rest API written in nodejs and a front in backbone.
The first version of the Rest API was in golang and this repository is an
extraction of it, for the record. It can be a source of inspiration on how to
use golang with json, mongodb (mgo), pat, securecookie (gorilla) and
[Mozilla Persona](http://www.mozilla.org/persona/).


How to use it?
--------------

[Install Go 1](http://golang.org/doc/install) and run this command:

    go get github.com/nono/koalab-golang-api
    koalab [-a address:port] [-h URL] [-m mongo] [-d database]


Credits
-------

♡2012 by Bruno Michel. Copying is an act of love. Please copy and share.

Released under the MIT license
