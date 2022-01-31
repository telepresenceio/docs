# Telepresence documentation

The Telepresence documentation "lives" at several different locations,
embedded in various Git repositories via [`git subtree`][].  This
repository acts as a rendezvous point for each of those locations.

[`git subtree`]: https://github.com/git/git/blob/master/contrib/subtree/git-subtree.txt

In this repository you will find `release/v${X}` branches that contain
the documentation for that release line of Telepresence:

 - `release/v1` The documentation for the legacy Telepresence 0.x line.
 - `release/v2.Y` The documentation for a given Telepresence 2 release line.
 - `release/v2` The documentation for ongoing Telepresence 2
   development; this is the "mainline" documentation of yet-unreleased
   Telepresence 2 versions.  Because of procedures around when
   subtrees get synced, this may lag behind what is in other
   repositories.
