# $Id$

AM_CFLAGS = @LIBFREEFARE_CFLAGS@
AM_CPPFLAGS = -I $(top_srcdir)/libucard -I $(top_srcdir)/common

bin_PROGRAMS = fidelite-info

fidelite_info_SOURCES = info.c
fidelite_info_LDADD = $(top_builddir)/libucard/libucard.la \
		       $(top_builddir)/common/libucard-convenience.la
