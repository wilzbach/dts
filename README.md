# dts

> A modern standard library for D.

What is `dts`?
--------------

A fresh and modern standard library for D aimed at being efficient and easy-to-use.
Users of Phobos will find it very familar whereas newcomers to the language should find it intuitive to use.

Why not improve Phobos?
-----------------------

While `dts` is based upon Phobos, many changes that were done are breaking and
can't be done in Phobos.

Design rationales
-----------------

- Allow functions to be used in `@nogc`
- Provide clear and consistent naming
- If required, provide performance choices to the user
- Only provide minimal, general-purpose and powerful building blocks

How can I use `dts`?
--------------------

Add it `"dts": "~>0.1"` to your `dub.json` or `dependency "dts" version="~>0.1"` to your `dub.sdl`

License
-------

Boost Software License - Version 1.0 - August 17th, 2003
