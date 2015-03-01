Unpack
======

Unpack is a generic archive unpacking tool. Based on the file paths in the
archive, it attempts to find an acceptable top level directory to extract to.

This script primarily exists because not everyone sticks to the convention of
creating archives with a base folder, and the myriad of compression tools lack
a standard interface (and reading man pages is a chore).

The code is available under the BSD license.


Currently supported formats
---------------------------

- tar (uncompressed, gzip, bzip2, lzma, xz)
- 7z
- rar
- zip
- gz
- bz2
- lzma
- xz
- lzo


Dependencies
------------

- p7zip >=9.x for 7z/rar/cab
- A recent tar


Installation
------------

To install for your user::

    python setup.py install --user

Or just symlink ``unpack`` to ``~/.local/bin/unpack``.
