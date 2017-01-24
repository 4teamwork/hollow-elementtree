# Hollow Elementtree

``elementtree`` is included in the Python standard library for some years now.
But we have the problem that we use older libraries which still have a
dependency to ``elementtree``, which is actually not installable by the newest
``setuptools`` version.

In order to awoid problems, we have released an empty ``elementtree==hollow``
package onto our internal PSC, so that the dependency is satisfied.
It does not ship the code though, but we expect all Pythons to include it by
default.
