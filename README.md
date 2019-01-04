
# macaroons

A Haskell macaroons implementation

Adapted from [jtanguy/hmacaroons](https://github.com/jtanguy/hmacaroons)

Changes:

  * Third party and first party caveats are separate constructors
  * Reduced the number of required dependencies
  * Verification is simplified, it returns a Bool.
  * [Single-file](src/Crypto/Macaroons.hs) implementation
