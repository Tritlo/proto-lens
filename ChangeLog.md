# ChangeLog

## v0.1.0.3
- In printing and parsing protocol buffers use/interpret escape
sequences in a way compatible with the Protocol Buffer
distribution's C/C++ escaping style, closing Issues #44 and
#45. This makes the text output incompatible with previous
versions; earlier versions will misinterpret text written by this
version and this version will misinterpret text written by
previous versions.
- Support reading text protocol buffers with single quote characters
(') for string delimiters, closing Issue #20.

## v0.1.0.2
- Expose more of protoc-gen-haskell to plugins.
- Support enum aliases.
- TextFormat prints enum names instead of numbers.

## v0.1.0.1
- Support ghc-8.
- Handle .proto files without a "package" declaration (#11).

## v0.1.0.0
- Initial version.
