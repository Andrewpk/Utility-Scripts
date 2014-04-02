Utility-Scripts
===============

Random utility scripts I create. Most likely in bash/shell, perl, or php.


## watchsync
watchsync is a utility with OS X specifically in mind (though it should
work with any OS that has [fswatch](http://manned.org/fswatch/0c99f664)
available in the path.

You give it an optional port, a local source
directory, and a remote target directory (in the form of
`user@remoteHost:targetDir`) and it'll watch the local directory for
changes.
When changes are found, they're immediately synched to the
remote directory, a timestamp is printed in the terminal along with any
files that were modified.

It's a work in progress and I haven't even
tested it yet tonight as I was just trying to make a simple one lined
script "github ready". YMMV.
