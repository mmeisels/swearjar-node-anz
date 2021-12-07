# swearjar-node

Profanity detection and filtering library.
Taken from Raymond's version and extended for ANZ swear words etc

## Installation

    npm install --save swearjaranz

## Usage

### swearjar.profane(text)

Returns true if the given string contains profanity.

    var swearjar = require('swearjar');
    swearjar.profane("hello there"); // false
    swearjar.profane("hello mother f-bomb"); // true

### swearjar.censor(text)

Replaces profanity with asterisks.

    var clean = swearjar.censor("f-bomb you"); // **** you

## Acknowledgements

`swearjar-node` is based on [Swearjar](https://github.com/joshbuddy/swearjar) (Ruby) and [Swearjar PHP](https://github.com/raymondjavaxx/swearjar-php).
