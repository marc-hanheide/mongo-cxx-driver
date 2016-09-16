This is a fork of the `26compat` version of `mongo-cxx-driver` to build a Debian package from it.

It uses the ideas from https://quentinsf.com/writings/debscons/ to generate a simple Debian binary package

Run this as `scons --prefix=/tmp/debroot --use-system-boost --full debian`

For everything else look at https://github.com/mongodb/mongo-cxx-driver/tree/26compat

