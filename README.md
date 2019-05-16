What is this fork good for ?
===================

This fork is meant to provide a patched AutoCompletion.cpp file. All other files are highly outdated.

It fixes this bug: https://github.com/notepad-plus-plus/notepad-plus-plus/issues/1038

Example bugged official version with bracket autocompletion:

Writing `(a(` results in `(a()` - the second bracket is not closed. This patched version fixes this.


How to build ?
===================

See issue linked above. Replace the .cpp file, and make a `unicode debug` build. A `unicode release` build will crash, because it lacks a signature.
