if USE_SYSTEM_SHARED_LIB
SUBDIRS = libcork libipset src
else
SUBDIRS = libsodium libcork libipset libcares libev src
endif

if ENABLE_DOCUMENTATION
SUBDIRS += doc
endif

ACLOCAL_AMFLAGS = -I m4
