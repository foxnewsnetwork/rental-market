# App Nav Structure

Something significant about mobile apps is that their app structure and lack of URI navigation header means that they have access to the so-called "2D" routing for free. Thus I will need to design an app structure that has the following capabilities:

- Able to show modals and pop-overs
- Has access to a drawer menu on the home route
- Has back buttons back

## Flatness in redux

## ID-able models

## Redux and flutter routing


## Comparable Mixin, Implementations, Extensions

## Why Dart & Flutter sucks

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