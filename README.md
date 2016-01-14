Fusandra - Cassandra Filesystem in Userspace (FUSE) implementation

[![No Maintenance Intended](http://unmaintained.tech/badge.svg)](http://unmaintained.tech/)

DESCRIPTION:

Fusandra is a proof of concept distributed filesystem, mountable anywhere and 
linked to an Apache Cassandra NoSQL database, therefore making it fault tolerant
 as well as extremely available.
Considering the usual properties filesystems offer and Cassandra's limitations, 
this is never intended to be an all purpose filsesystem, although it could have 
a few interesting use cases.


USAGE

To use Fusandra you'll need a running instance of Cassandra with no authentication.
Fusandra will automatically create all the structures it needs whithin Cassandra
on its first run

	chmod +x fusandra
	./fusandra directory_to_be_mounted


NOTES

This is a usable, yet very experimental project. Proceed with caution.


TODO

Symlinks and other filesystem functionality that isn't basic file/dir manipulation.
Any and all configuration options, including command line options to choose the 
Cassandra instance to use, authentication options, etc.


LICENSE

Copyright (C) 2013 by Filipe Gonçalves < the.wa.syndrome@gmail.com >

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
