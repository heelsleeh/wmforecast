SUBDIRS = icons
bin_PROGRAMS = wmforecast
wmforecast_SOURCES = wmforecast.c
dist_man_MANS = wmforecast.1

AM_CFLAGS = $(libxml2_CFLAGS) $(libcurl_CFLAGS) $(X11_CFLAGS)
AM_CPPFLAGS =  -DDATADIR=\"$(pkgdatadir)\"
LIBS += $(libxml2_LIBS) $(libcurl_LIBS) $(X11_LIBS) -lWINGs -lwraster -lWUtil

desktopdir = $(datadir)/applications
dist_desktop_DATA = wmforecast.desktop

EXTRA_DIST = autogen.sh README.md
