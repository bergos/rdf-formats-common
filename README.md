# rdf-formats-common

[![Build Status](https://travis-ci.org/rdf-ext/rdf-formats-common.svg?branch=master)](https://travis-ci.org/rdf-ext/rdf-formats-common)
[![NPM Version](https://img.shields.io/npm/v/rdf-formats-common.svg?style=flat)](https://npm.im/rdf-formats-common)

This module loads parsers and serializers for the most common formats.
The `Parsers` and `Serializers` classes of RDF-Ext are used to handle different media types.

## Usage

Create a new object:

    var formats = require('rdf-formats-common')();

The parsers are loaded into `formats.parsers` and the serializers are loaded into `formats.serializers`.

It's also possible to load the formats into an existing object:

    require('rdf-formats-common')(formats)
