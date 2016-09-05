# Swift: Raindrops

Write a program that converts a number to a string, the contents of which depends on the number's factors.

- If the number contains 3 as a factor, output 'Pling'.
- If the number contains 5 as a factor, output 'Plang'.
- If the number contains 7 as a factor, output 'Plong'.
- If the number does not contain 3, 5, or 7 as a factor,
  just pass the number's digits straight through.

## Examples

- 28's factors are 2, 4, **7**, 14.
  - In raindrop-speak, this would be a simple "Plong".
- 30's factors are 2, **3**, **5**, 6, 15.
  - In raindrop-speak, this would be a "PlingPlang".
- 34 only has two factors- 2 and 17.
  - Raindrop-speak doesn't know what to make of that,
    so it just goes with the straightforward "34".

In order to use Swift, you must be running Xcode version 7.3 or greater which is available at [Apple's developer center][appledev].

[appledev]: https://developer.apple.com/xcode/downloads/

The exercises use XCTest.

See [this guide][exercism-xcode-swift] for details about how to create the project in XCode and run the tests.

[exercism-xcode-swift]: https://github.com/exercism/xswift/blob/master/docs/TESTS.md

## Source

A variation on a famous interview question intended to weed out potential candidates. [http://jumpstartlab.com](http://jumpstartlab.com)

This exercise is from the [Swift][swift] track on [Exercism][exercism]

[exercism]: http://exercism.io
[swift]: http://exercism.io/languages/swift



