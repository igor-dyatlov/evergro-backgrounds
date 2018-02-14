backgroundsdir  = $(datadir)/backgrounds
evergrodir = $(DESTDIR)$(backgroundsdir)/evergro

SUBDIRS = \
	backgrounds

EXTRA_DIST = \
	AUTHORS

install-data-hook:
	cp -Rv $(EXTRA_DIST) $(evergrodir)

uninstall-hook:
	test -e $(evergrodir) && rm -rfv $(evergrodir)
