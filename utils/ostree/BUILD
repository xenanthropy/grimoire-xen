cd $SOURCE_DIRECTORY &&

# Forcing curl over soup currently until flatpak has ostree sub-depends
./configure --prefix=$TRACK_ROOT/usr $OPTS --with-gpgme=yes --with-curl=yes --with-soup=no &&
default_build
