Role Name
=========

This role contains common definitions used by:

* flyingmachine.clojure-uberjar-webapp-app
* flyingmachine.clojure-uberjar-webapp-nginx
* flyingmachine.datomic-free

Role Variables
--------------

* `clojure_uberjar_webapp_domain` must be set by you.
* `clojure_uberjar_webapp_domain_dashed` defaults to a derivation of
  `clojure_uberjar_webapp_domain`, where all periods are replaced with
  dashes. Many other vars are derived from
  `clojure_uberjar_webapp_domain_dashed`.

Dependencies
------------

None

Example Playbook
----------------

This role is not meant to be used on its own.

License
-------

MIT

Author Information
------------------

* Daniel Higginbotham
* http://twitter.com/nonrecursive
* http://www.braveclojure.com/
