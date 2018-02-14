backgrounddir = $(datadir)/backgrounds/evergro

background_DATA = \
	Dragonfly.jpg \
	Forest-Falls.jpg \
	Iguana.jpg \
	River.jpg \
	Snow-Leopard.jpg \
	Spider.jpg \
	Stone-Beach.jpg \
	Tukan.jpg \
	White-Tiger.jpg \
	Wind-Farm.jpg

metadata_in_files = evergro-backgrounds.xml.in
metadata_DATA = $(metadata_in_files:.xml.in=.xml)
metadatadir = $(datadir)/gnome-background-properties

metadata_cinnamon_DATA = $(metadata_DATA)
metadata_cinnamondir = $(datadir)/cinnamon-background-properties
metadata_mate_DATA = $(metadata_DATA)
metadata_matedir = $(datadir)/mate-background-properties

noinst_DATA = evergro-backgrounds.xml.in

EXTRA_DIST = $(background_DATA)

edit = sed -e 's|@BACKGROUNDDIR[@]|$(backgrounddir)|g'

evergro-backgrounds.xml: evergro-backgrounds.xml.in
	$(edit) $< >$@

CLEANFILES = $(srcdir)/evergro-backgrounds.xml

DISTCLEANFILES = \
	$(CLEANFILES)
