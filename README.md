Momiji
=====

Momiji is a python script for downloading folder icons for your anime collection!
Do note that it is currently OS X. Future commits may add support for Linux and/or Windows.
To use it, open up your terminal and run:

    ./momiji <anime-collection-folder-name>;

Momiji will then run through that folder and assign an icon to any of the folders inside
that it can find a search result for on [MAL](http://myanimelist.net/). The
algorithm for doing so is fairly primitive but it gets the job done for most of my collection.

Momiji relies on two binaries in order to create and set the folder icons. The first of which
is ImageMagick's 'convert' utility. I recommend using [Homebrew](http://mxcl.github.com/homebrew/)
and running:

    brew install imagemagick

The second binary will be automatically downloaded upon first run and will be placed in Momiji's
working directory. I would suggest running Momiji in it's downloaded location for the time being
until a later commit handles properly storing and running this binary.

If you find any bugs, want to push any patches or just want to yell at me, feel free to do so on
[Momiji's github page](https://github.com/zerotri/momiji).