# Proses

Copyright (c) 2019 Seán D. Murray
SEE MIT LICENSE FILE

Make writing node easier, prettier and less error prone. Writes and reads more like prose

This is a wrapper module for the various prose modules. If you're using most
the of the prose modules just include this and it will get all the others.

## Usage

```javascript

// Util to determin var types. Uses Nil (undefined or null) concept!
const { isit_util } = require('proses');

// Util for number manipulation
const { number_util } = require('proses');

// Util for string manipulation
const { string_util } = require('proses');

// Use for to get a self cleaning temp etc.
const { file_util } = require('proses');

// Util for array manipulation
const { array_util } = require('proses');

// Util for object manipulation
const { object_util } = require('proses');

// OS util for help with post run cleanup, get command line args, envirnment args etc.
const { os_util } = require('proses');

// Promise util, like running an array of promises in sequence.
const { promise_util } = require('proses');

```


