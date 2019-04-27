include $(top_srcdir)/config/Rules.am

pkgdatadir = $(libexecdir)/@PACKAGE@/zfs-tests/tests/functional/ctime

dist_pkgdata_SCRIPTS = \
	ctime_001_pos.ksh \
	cleanup.ksh \
	setup.ksh

pkgexecdir = $(libexecdir)/@PACKAGE@/zfs-tests/tests/functional/ctime

pkgexec_PROGRAMS = ctime
ctime_SOURCES = ctime.c
