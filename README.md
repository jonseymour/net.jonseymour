NAME
----
net.jonseymour

DESCRIPTION
-----------
A collection of software written by Jon Seymour.

LICENSING
---------
Refer to each submodule for the licensing that applies to each.

PACKAGE NAMING STANDARDS
------------------------
* net.jonseymour.next.* 

  is reserved for unstable code whose API may change. Most experimental development will be done here. This code is not suitable for reference by third parties.
  Code in this namespace may depend on code in net.jonseymour.v{N}

* net.jonseymour.v{n}.*

  where {n} is an integer is reserved for stable version of API code that will only change in well controlled ways. This code is suitable for reference by third parties. No code in this namespace
  will depend on code in net.jonseymour.next. New version numbers, {n}, will be allocated to cope with major structural change in an API.

COPYRIGHT
---------
(C) Jon Seymour 2014-