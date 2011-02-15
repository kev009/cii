AM_CPPFLAGS = -I$(top_srcdir)/include

lib_LTLIBRARIES = libcii.la
libcii_la_includedir = $(top_srcdir)/include
libcii_la_SOURCES = ap.c \
		    arena.c \
		    arith.c \
		    array.c \
		    assert.c \
		    atom.c \
		    bit.c \
		    chan.c \
		    except.c \
		    fmt.c \
		    list.c \
		    mem.c \
		    mp.c \
		    ring.c \
		    seq.c \
		    set.c \
		    stack.c \
		    str.c \
		    table.c \
		    text.c \
		    xp.c
# Needs work:
#memchk.c
#thread.c
#thread-nt.c
#swtch.s

# Conditional
# memcmp.c
# memmove.c
# strncmp.c

libcii_la_CPPFLAGS = -I$(top_srcdir)/include
libcii_la_LDFLAGS = -version-info 2:0:0
