headerdir = $(prefix)/include/libbson-@BSON_API_VERSION@
header_DATA = $(INST_H_FILES)

INST_H_FILES += \
	src/bson/bson.h \
	src/bson/bson-atomic.h \
	src/bson/bson-clock.h \
	src/bson/bson-compat.h \
	src/bson/bson-context.h \
	src/bson/bson-endian.h \
	src/bson/bson-error.h \
	src/bson/bson-iter.h \
	src/bson/bson-json.h \
	src/bson/bson-keys.h \
	src/bson/bson-macros.h \
	src/bson/bson-md5.h \
	src/bson/bson-memory.h \
	src/bson/bson-oid.h \
	src/bson/bson-reader.h \
	src/bson/bson-string.h \
	src/bson/bson-types.h \
	src/bson/bson-utf8.h \
	src/bson/bson-writer.h

if OS_WIN32
INST_H_FILES += src/bson/bson-stdint-win32.h
endif

NOINST_H_FILES += \
	src/bson/bson-private.h \
	src/bson/bson-context-private.h \
	src/bson/bson-thread-private.h

libbson_1_0_la_SOURCES += \
	src/bson/bson.c \
	src/bson/bson-clock.c \
	src/bson/bson-context.c \
	src/bson/bson-error.c \
	src/bson/bson-iter.c \
	src/bson/bson-json.c \
	src/bson/bson-keys.c \
	src/bson/bson-md5.c \
	src/bson/bson-memory.c \
	src/bson/bson-oid.c \
	src/bson/bson-reader.c \
	src/bson/bson-string.c \
	src/bson/bson-utf8.c \
	src/bson/bson-writer.c

EXTRA_DIST += \
	bson/bson-config.h.in \
	bson/bson-version.h.in

DISTCLEANFILES += \
	bson/bson-stdint.h