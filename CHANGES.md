# Version 1.0.0.0

* New maintainer: Peter Jones

* Widen version bounds for dependencies.

* The `noio` flag is deprecated and will be removed in the next major release.

* Minor releases:

  - 1.0.1: Build on GHC 9.x and open dependency bounds.

# Version 0.0.0.12

* Opposing lenses for `lines` and `unlines` and `words` and `unwords`.
  Brought closer in line with `pipes-bytestring` again. Removed `count`, which
  was wrong. Scrapped `Iso` and the `profunctors` dependency.

# Version 0.0.0.11

* Updated to use streaming-commons in place of text-stream-decoding.

# Version 0.0.0.10

* Documentation changes.


# Version 0.0.0.9

* Documentation changes.

# Version 0.0.0.7

 * Used the new text-stream-decoding package
 * Separated IO and Encoding modules adding flag -fnoio

 # Version 0.0.0.5

 * Rearranged internal modules


 # Version 0.0.0.4

 * Altered bad haddock markup


 # Version 0.0.0.3

 * Actually added changelog


 # Version 0.0.0.2

 * Omit `stdinLn` as likely to be dangerous through misunderstanding.


 # Version 0.0.0.1

 * Rearrange order of 'Internal' materials.
