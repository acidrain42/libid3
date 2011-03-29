# Used to build Makefile.in

INCLUDES = -I$(top_builddir)/include -I$(srcdir)/../include

lib_LTLIBRARIES = libid3.la
libid3_la_SOURCES = id3.c md5.c
libid3_la_LDFLAGS = -version-info @SHARED_LIB_VERSION@
noinst_HEADERS = md5.h
