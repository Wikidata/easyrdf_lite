EasyRdf Lite
=======
EasyRdf Lite is a customized version of [EasyRdf] – a PHP library designed to make it easy to consume and produce RDF.
EasyRdf Lite was created for [Wikidata]. Since 2015 Wikidata uses [Purtle] to generate the RDF.

How to reduce EasyRdf to EasyRdf Lite
------------

* Download the [EasyRdf source code]
* Use the `lib` folder as parent
* Delete the following folders below EasyRdf: `Http`, `Parser`, `Sparql`
* Delete the following files below EasyRdf: `GraphStore.php`, `Http.php`, `Parser.php`, `ParsedUri.php`
* Adjust `EasyRdf.php` by deleting all `require`s of the deleted files and folders

Licensing
---------

The EasyRdf library and tests are licensed under the [BSD-3-Clause] license.
The examples are in the public domain, for more information see [UNLICENSE].


[EasyRdf]:http://www.easyrdf.org/
[EasyRdf source code]:https://github.com/njh/easyrdf/
[Wikidata]:https://www.wikidata.org/
[Purtle]:https://www.mediawiki.org/wiki/Purtle

[BSD-3-Clause]:http://www.opensource.org/licenses/BSD-3-Clause
[UNLICENSE]:http://unlicense.org/
