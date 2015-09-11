
An attempt at making OpenCV 3.x PPAs for Ubuntu 'trusty' and 'precise' (for
now).   I needed PPA to test some code automatically at
[http://travis-ci.com](Travis).  This is my first attempt at building a PPA so
apologies for any terribleness (and it's a big package).  The resulting
packages are hosted at Launchpad:

    [https://launchpad.net/~amarburg/+archive/ubuntu/opencv3](https://launchpad.net/~amarburg/+archive/ubuntu/opencv3)


As always, I welcome pull requests and comments to improve the quality of the
packages.

I did not explicitly try to strip out code but when packages got in my way, I
disabled them.  Please see <code>debian/changelog</code> for a discussion of
what's been removed.
