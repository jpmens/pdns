pkglib_LTLIBRARIES = liblmdbbackend.la

EXTRA_DIST = OBJECTFILES OBJECTLIBS

liblmdbbackend_la_SOURCES = \
	lmdbbackend.cc lmdbbackend.hh

liblmdbbackend_la_LDFLAGS = -module -avoid-version
liblmdbbackend_la_LIBADD = $(LMDB_LIBS)

