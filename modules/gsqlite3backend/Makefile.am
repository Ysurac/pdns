AM_CPPFLAGS=$(THREADFLAGS) $(BOOST_CPPFLAGS)
pkglib_LTLIBRARIES = libgsqlite3backend.la

EXTRA_DIST=OBJECTFILES OBJECTLIBS \
	schema.sqlite3.sql nodnssec-3.x_to_3.4.0_schema.sqlite3.sql dnssec-3.x_to_3.4.0_schema.sqlite3.sql

dist_doc_DATA=schema.sqlite3.sql nodnssec-3.x_to_3.4.0_schema.sqlite3.sql dnssec-3.x_to_3.4.0_schema.sqlite3.sql

libgsqlite3backend_la_SOURCES=gsqlite3backend.cc gsqlite3backend.hh

libgsqlite3backend_la_LDFLAGS=-module -avoid-version
