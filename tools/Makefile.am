bin_PROGRAMS = gnomesu

AM_CPPFLAGS =\
	-DGETTEXT_PACKAGE="\"$(GETTEXT_PACKAGE)\""\
	-DLOCALEDIR="\"$(datadir)/locale\""\
	-DGNOMESU_VERSION="\"$(VERSION)\""\
	-DGNOMESU_PREFIX="\"$(prefix)\""\
	-DG_DISABLE_DEPRECATED\
	$(LIBGNOMESU_CFLAGS)\
	$(GNOMESU_CFLAGS)\
	-I$(top_srcdir)/src

gnomesu_SOURCES = gnomesu.c
gnomesu_LDFLAGS = $(GNOMESU_LIBS)
gnomesu_LDADD = ../src/libgnomesu.la

EXTRA_DIST = $(gnomesu_SOURCES)
