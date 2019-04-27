include $(top_srcdir)/config/Rules.am

pkgdatadir = $(libexecdir)/@PACKAGE@/zfs-tests/tests/functional/truncate

dist_pkgdata_SCRIPTS = \
	setup.ksh \
	cleanup.ksh \
	truncate_001_pos.ksh \
	truncate_002_pos.ksh \
	truncate_timestamps.ksh

dist_pkgdata_DATA = \
	truncate.cfg

pkgexecdir = $(libexecdir)/@PACKAGE@/zfs-tests/tests/functional/truncate

pkgexec_PROGRAMS = truncate_test
truncate_test_SOURCES = truncate_test.c
