TOPDIR = ../../..
include $(TOPDIR)/src/include/builddefs

TESTDIR = $(PCP_VAR_DIR)/testsuite/ganglia/gangliatest.64
QAFILES = $(shell echo *.rrd)

default default_pcp setup: 

install install_pcp:
	$(INSTALL) -m 755 -d $(TESTDIR)
	$(INSTALL) -m 644 $(QAFILES) $(TESTDIR)

include $(BUILDRULES)
