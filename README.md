Yikes!
======
Yet another yaml parser, ( but incremental! ).
The fastest way to propagates changes in a YAML string into an ImmutableJS structure.

Because of reasons.

## In JavaScript....
We cannot natively work with YAML we need to convert it into a javascript structure, much like JSON.
Moreover, we're cool people. And we want to convert that into an [ImmutableJS](https://facebook.github.io/immutable-js) structure, which can be expensive.
So the idea is to make an AST parser, that is evented - spitting out incremental changes.

## TODO: Get an example
