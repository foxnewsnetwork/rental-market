# App Nav Structure

After an earnest 24 chapter attempt (documented in this journal) to build a dart flutter app, I've decided to give up for the following reasons:

## Why Dart sucks

- `enum` can't extend `Comparable`
- `typedef` can't type-alias (e.g. `typedef Blah = Comparable<Dog>` won't work)
- No support for immutability beyond manually copying of everything
- No `const () => 'whatever'` functions
- Useless amounts of `new`, `const`, and other pointless constructor mechanisms
- No web development support
- Can't `extend` String or have any other support for typed strings
- No `union` types
- Very difficult to debug runtime error messages
- Flutter is difficult to work with with regards to integration with redux
- Language features from 2012 still not implemented today (e.g. Google sucks)

## Solution

Next up is facebook's react-native, except I will build it in OOCaml (via reasonML), this is, of course, a blind decision at this point, however, here are my hopes and dreams for what reasonML can be:

- Strongly typed language
- Functional approach
- Immutability
- Strong community support

## References

- Dead code repo: https://github.com/foxnewsnetwork/rental_market_flutter
- react native docs https://facebook.github.io/react-native/
- reasonML react native connect: https://github.com/reasonml-community/bs-react-native
- reasonML https://reasonml.github.io/