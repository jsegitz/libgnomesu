ACLOCAL_AMFLAGS = -I m4

SUBDIRS = src su-backend pam-backend tools po doc

pkgfilesdir = $(libdir)/pkgconfig
pkgfiles_DATA = libgnomesu-1.0.pc

EXTRA_DIST =\
	libgnomesu-1.0.pc.in\
	intltool-merge.in\
	intltool-update.in\
	intltool-extract.in

DISTCLEANFILES =\
	intltool-merge\
	intltool-update\
	intltool-extract

DISTCHECK_CONFIGURE_FLAGS = --disable-setuid-error --disable-install-pam
