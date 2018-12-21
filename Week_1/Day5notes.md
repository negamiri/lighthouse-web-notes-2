# Day 5 notes

## Lecture: Modules and testing

Predicate = tester function ==> takes an array and returns a boolean

Mocha
- Can create report (on command line):

  mocha file name --reporter markdown
  turn it into a file
  mocha file name --reporter markdown > docs.md

## Notes

* Library: an independent collection of code that can be used by programs (not JS specific)
* Module: S code in a seperate file, that can be required by other JS programs
* Package: a collection of JS modules, with a package.json, usually published on NPM

- node_modules directory does not need to be committed to your project's git repo
- package.json _should_ be committeed to your project's git repo

- Each dependency has its own subdirectory in the node_modules directory