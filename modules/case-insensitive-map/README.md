# `case-insensitive-map`
This module is a case-insensitive map. It exposes the same interface as the Javascript `Map` but with case-insensitive keys. For example, in this Map the keys `key1` and `KeY1` are considered the same in all the functions that interact with the Map. Internally, it uses a Javascript `Map` and passes each key through the `toUpperCase` function before passing it to the `Map`.