# Prose

Copyright (c) 2019 Seán D. Murray
SEE MIT LICENSE FILE

Make writing node easier, prettier and less error prone. Writes and reads more like prose

This is a wrapper module for the various Prose modules. If your using most
the of the Prose modules just include this and it will get all the others.

## Usage

```javascript

// Util to determin var types. Uses Nil (undefined or null) concept!
const { isit_util } = require('Prose');

// Util for number manipulation
const { number_util } = require('prose_number');

// Util for string manipulation
const { string_util } = require('Prose');

// Use for to get a self cleaning temp etc.
const { file_util } = require('Prose');

// Util for array manipulation
const { array_util } = require('Prose');

// Util for object manipulation
const { object_util } = require('Prose');

// OS util for help with post run cleanup, get command line args, envirnment args etc.
const { os_util } = require('Prose');

// Promise util, like running an array of promises in sequence.
const { promise_util } = require('Prose');

```


