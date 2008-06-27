# Makefile.am for ntsutils/src

yncludedir = @yncludedir@/ntsutils

client_DATA =			\
	ntsutils.ycp

ynclude_DATA =			\
	helps.ycp		\
	wizards.ycp		\
	dialogs.ycp		\
	complex.ycp

desktop_DATA =			\
	ntsutils.desktop

module_DATA =			\
	Ntsutils.ycp

# create a symlink for local build, #145327
ntsutils:
	ln -sf . $@
ycpchook = ntsutils

EXTRA_DIST = $(client_DATA) $(ynclude_DATA) $(module_DATA) $(desktop_DATA)

include $(top_srcdir)/Makefile.am.common
