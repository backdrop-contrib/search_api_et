Search API Entity Translation
========
WARNING: This module should be considered alpha status and not ready
for production sites, which is why there is currently not a release for it.
Use at your own risk.

This module creates a multilingual node index for nodes translated
by the Entity Translation module, which translates nodes on a field-by-field
basis.

Requirements
------------
This module requires that the following modules are also enabled:

- [Entity Translation](https://github.com/backdrop-contrib/entity_translation)
- [Search API](https://github.com/backdrop-contrib/search_api)
- One of the Search API server modules like search_api_db or search_api_solr
- (Not required) [Search API ET DB](https://github.com/backdrop-contrib/search_api_et_db)
  Fixes duplicate results/incorrect facet counts returned for translated entities.
  module from Drupal.


Installation
------------

- Install this module using the official Backdrop CMS instructions at
  https://docs.backdropcms.org/documentation/extend-with-modules.

- Make sure you have a node type that's translated by Entity Translation

- Visit the configuration page for the search index under 
  Administration > Configuration > Search > Search API > Default multlingual
  node index
  admin/config/search/search_api/index/default_multilingual_node_index

  Make sure you also have a search Server set up first as well


Issues
------

Bugs and Feature Requests should be reported in the Issue Queue:
https://github.com/backdrop-contrib/search_api_et


Current Maintainers
-------------------

- [Benjamin Wheeler](https://github.com/bennybobw)
- [Anthony Nemirovsky](https://github.com/anemirovsky)
- [Peter Haight](https://github.com/Dawnthorn)


Credits
-------
- Ported to Backdrop CMS by [Benjamin Wheeler](https://github.com/bennybobw).
- Drupal maintainers:
-- [danielnolde](https://www.drupal.org/u/danielnolde).
-- [idebr](https://www.drupal.org/u/idebr).
-- [maciej.zgadzaj](https://www.drupal.org/u/maciejzgadzaj).
-- [thepanz](https://www.drupal.org/u/thepanz).
- Drupal Search API Entity Translation v1 is sponsored by [wunderkraut](http://www.wunderkraut.com/).
- Version 2.x was sponsored by [Commerce Guys](http://www.commerceguys.com/) and [Liip AG](http://www.liip.ch/).


License
-------
This project is GPL v2 software.
See the LICENSE.txt file in this directory for complete text.
