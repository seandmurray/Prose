# Proses

Copyright (c) 2020 Seán D. Murray
SEE MIT LICENSE FILE

Make writing node easier, prettier and less error prone. Writes and reads more like prose

This is a wrapper module for the various prose modules. If you're using most
the of the prose modules just include this and it will get all the others.

## Usage

```javascript

// A logic utility, Nil is either NULL or undefined.
const { prose_is } = require('proses');

// Util to determine variable types.
const { prose_isit } = require('proses');

// Util for number manipulation
const { prose_number } = require('proses');

// Util for string manipulation
const { prose_string } = require('proses');

// Use for to get a self cleaning temp etc.
const { prose_file } = require('proses');

// Util for array manipulation
const { prose_array } = require('proses');

// Util for object manipulation
const { prose_object } = require('proses');

// OS util for help with post run cleanup, get command line args, envirnment args etc.
const { prose_os } = require('proses');
```
