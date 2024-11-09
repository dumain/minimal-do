# Minimal Do

This is minimal do forked from apenwarr do.

This do is an implementation of redo that does *not* check dependencies
or support incremental builds.  It will never rebuild a target it has
already built, unless you use -c.

You can include it in a redo based project to allow it to
be built without a redo install.  For serious work install
[Apenwarr/redo](https://github.com/apenwarr/redo) or some other complete
implementation of redo.
