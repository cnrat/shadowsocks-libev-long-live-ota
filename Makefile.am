if USE_SYSTEM_SHARED_LIB
SUBDIRS = libcork libipset src
else
SUBDIRS = libsodium libcork libipset libudns libev src
endif

ACLOCAL_AMFLAGS = -I m4

pkgconfiglibdir = $(libdir)/pkgconfig
pkgconfiglib_DATA = shadowsocks-libev.pc
