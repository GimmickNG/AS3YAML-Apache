# AS3YAML-Apache
A fork of the AS3YAML library using the new AS3Commons Collections library (licensed under Apache 2)
Imported from the [AS3YAML Google Code Archive](https://code.google.com/archive/p/as3yaml/), but with the collections library used changed to the new [AS3Commons Collections framework](https://github.com/AS3Commons/as3commons-collections) in order to comply with the Apache 2.0 license instead of the MPL 1.1 license.

Note: As it stands, the AS3YAML library source is licensed under the MIT license. However, since the underlying AS3Commons Collections library it uses is licensed under the Apache 2.0 license, this fork is also licensed under the Apache 2.0 license.

There are 2 versions in releases, one with the dependencies included, and one without - that is, one with the AS3Commons Collections library, and one without. If you are already using the AS3Commons Collections library in your project, you may use the one with external dependencies to avoid the overhead of reincluding the same files; otherwise, you can use the version with the dependency included.

Usage is the same as the AS3YAML library, and efforts have been taken to not modify the underlying interface; as a result, it can be used as a drop-in replacement for the AS3YAML (Google Code Archive) library, if use of the Mozilla Public License is not desired. For documentation and more details, please see the original project as linked above.
