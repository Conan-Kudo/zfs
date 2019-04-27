include $(top_srcdir)/config/Rules.am

pkgdatadir = $(libexecdir)/@PACKAGE@/zfs-tests/tests/functional/cp_files

dist_pkgdata_SCRIPTS = \
	cp_files_001_pos.ksh \
	cleanup.ksh \
	setup.ksh

pkgexecdir = $(libexecdir)/@PACKAGE@/zfs-tests/tests/functional/cp_files

pkgexec_PROGRAMS = cp_files
cp_files_SOURCES= cp_files.c
