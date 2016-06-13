# Changelog

## v0.2.7

* Upgrade vendored `browser-resolve` to latest version to ensure compatibility with Node v6.

## v0.2.6

* Make sure we don't rename a bound file if the same file is required multiple times. Fixes [#19](https://github.com/Shopify/sprockets-commoner/issues/19).

## v0.2.5

* Add `cache_key` to processor to make sure we bust the cache when processor config changes.

## v0.2.4

* Enable completely optimizing away empty module definitions.

## v0.2.3

* Only avoid imports that won't be processed by Commoner if we actually use the module.

## v0.2.2

* Don't cache Babel output as this can lead to bugs.
* Avoid imports of files that won't be processed by Commoner, to defend against bugs.
* Exclude vendor/bundle by default.

## v0.2.1

* Fix bug with `browser` field stubbing out modules.
* Add support for requiring CoffeeScript files that don't define any globals.

## v0.2.0

* Add support for requiring JSON files.

## v0.1.3

* Backport fixes from v0.2.3

## v0.1.2

* Backport fixes from v0.2.2

## v0.1.1

* Backport fixes from v0.2.1.

## v0.1.0

* Initial version.