# Generated automatically from Makefile.in by configure.
# Makefile.in generated automatically by automake 1.4a from Makefile.am

# Copyright (C) 1994, 1995-8, 1999 Free Software Foundation, Inc.
# This Makefile.in is free software; the Free Software Foundation
# gives unlimited permission to copy and/or distribute it,
# with or without modifications, as long as this notice is preserved.

# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY, to the extent permitted by law; without
# even the implied warranty of MERCHANTABILITY or FITNESS FOR A
# PARTICULAR PURPOSE.


SHELL = /bin/sh

srcdir = .
top_srcdir = ..
prefix = /usr/local
exec_prefix = ${prefix}

bindir = ${exec_prefix}/bin
sbindir = ${exec_prefix}/sbin
libexecdir = ${exec_prefix}/libexec
datadir = ${prefix}/share
sysconfdir = ${prefix}/etc
sharedstatedir = ${prefix}/com
localstatedir = ${prefix}/var
libdir = ${exec_prefix}/lib
infodir = ${prefix}/info
mandir = ${prefix}/man
includedir = ${prefix}/include
oldincludedir = /usr/include

DESTDIR =

pkgdatadir = $(datadir)/pose
pkglibdir = $(libdir)/pose
pkgincludedir = $(includedir)/pose

top_builddir = ..

ACLOCAL = /home/salva/elektrofunken/palm_fun/PalmOSEmuReborn/BuildUnix/missing aclocal
AUTOCONF = /home/salva/elektrofunken/palm_fun/PalmOSEmuReborn/BuildUnix/missing autoconf
AUTOMAKE = /home/salva/elektrofunken/palm_fun/PalmOSEmuReborn/BuildUnix/missing automake
AUTOHEADER = /home/salva/elektrofunken/palm_fun/PalmOSEmuReborn/BuildUnix/missing autoheader

INSTALL = /usr/bin/install -c
INSTALL_PROGRAM = ${INSTALL}
INSTALL_DATA = ${INSTALL} -m 644
INSTALL_SCRIPT = ${INSTALL_PROGRAM}
INSTALL_STRIP_FLAG =
transform = s,x,x,

NORMAL_INSTALL = :
PRE_INSTALL = :
POST_INSTALL = :
NORMAL_UNINSTALL = :
PRE_UNINSTALL = :
POST_UNINSTALL = :
build_alias = x86_64-unknown-linux-gnu
build_triplet = 
host_alias = x86_64-unknown-linux-gnu
host_triplet = 
target_alias = x86_64-unknown-linux-gnu
target_triplet = 
AR = ar
CC = gcc
CPP = gcc -E
CXX = c++
GLLIB = -lGLU -lGL
MAKEINFO = /home/salva/elektrofunken/palm_fun/PalmOSEmuReborn/BuildUnix/missing makeinfo
PACKAGE = pose
POSER_CFLAGS =  -DPLATFORM_UNIX=1 -D__PALMOS_TRAPS__=0 -DEMULATION_LEVEL=EMULATION_UNIX -O2  -DHAS_PROFILING=0 -DNDEBUG  -fexceptions -Wall -Wno-multichar -Wno-unknown-pragmas -Wno-conversion 
POSER_CXXFLAGS =  -DPLATFORM_UNIX=1 -D__PALMOS_TRAPS__=0 -DEMULATION_LEVEL=EMULATION_UNIX -O2  -DHAS_PROFILING=0 -DNDEBUG  -fexceptions -Wall -Wno-multichar -Wno-unknown-pragmas -Wno-conversion 
RANLIB = ranlib
THREAD_FLAGS = -D_REENTRANT -DNoNanoSleep -DPthreadDraftVersion=10
THREAD_LIBS = -lpthread
THREAD_SRC = 
VERSION = 0

SUFFIXES = .cpp

VPATH = $(srcdir)/../../SrcShared/Gzip:

LOCAL_CFLAGS = 

CFLAGS = $(POSER_CFLAGS) $(LOCAL_CFLAGS)
CXXFLAGS = $(POSER_CXXFLAGS) $(LOCAL_CFLAGS)

INCLUDES = -I$(srcdir)/../../SrcShared/Gzip

noinst_LIBRARIES = libposergzip.a

SRC_GZIP = bits.c									crypt.h									deflate.c								gzip.h									inflate.c								lzw.h									revision.h								tailor.h								trees.c									util.c


libposergzip_a_SOURCES = $(SRC_GZIP)
mkinstalldirs = $(SHELL) $(top_srcdir)/mkinstalldirs
CONFIG_CLEAN_FILES = 
LIBRARIES =  $(noinst_LIBRARIES)


DEFS =  -DX_DISPLAY_MISSING=1 -DHAVE_DIRENT_H=1 -DSTDC_HEADERS=1 -DHAVE_ENDIAN_H=1 -DHAVE_FCNTL_H=1 -DHAVE_LIMITS_H=1 -DHAVE_STRINGS_H=1 -DHAVE_SYS_TIME_H=1 -DHAVE_UNISTD_H=1 -DHAVE_TYPE_SOCKLEN_T=1 -DHAVE_ALLOCA_H=1 -DHAVE_ALLOCA=1 -DHAVE_MKDIR=1 -DHAVE_MKSTEMP=1 -DHAVE_TEMPNAM=1 -DHAVE_GL=1 -DHAVE_GL_GLU_H=1 -DHAVE_LIBFLTK=1  -I. -I$(srcdir) 
CPPFLAGS =  -I/usr/include/FL/include
LDFLAGS =  -L/usr/include/FL/lib
LIBS = 
X_CFLAGS = 
X_LIBS = 
X_EXTRA_LIBS = 
X_PRE_LIBS = 
libposergzip_a_LIBADD = 
libposergzip_a_OBJECTS =  bits.o deflate.o inflate.o trees.o util.o
COMPILE = $(CC) $(DEFS) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(AM_CFLAGS) $(CFLAGS)
CCLD = $(CC)
LINK = $(CCLD) $(AM_CFLAGS) $(CFLAGS) $(LDFLAGS) -o $@
DIST_COMMON =  Makefile.am Makefile.in


DISTFILES = $(DIST_COMMON) $(SOURCES) $(HEADERS) $(TEXINFOS) $(EXTRA_DIST)

TAR = gtar
GZIP_ENV = --best
DEP_FILES =  .deps/bits.P .deps/deflate.P .deps/inflate.P .deps/trees.P \
.deps/util.P
SOURCES = $(libposergzip_a_SOURCES)
OBJECTS = $(libposergzip_a_OBJECTS)

all: all-redirect
.SUFFIXES:
.SUFFIXES: .S .c .cpp .o .s
$(srcdir)/Makefile.in: Makefile.am $(top_srcdir)/configure.in $(ACLOCAL_M4) 
	cd $(top_srcdir) && $(AUTOMAKE) --foreign Gzip/Makefile

Makefile: $(srcdir)/Makefile.in  $(top_builddir)/config.status $(BUILT_SOURCES)
	cd $(top_builddir) \
	  && CONFIG_FILES=$(subdir)/$@ CONFIG_HEADERS= $(SHELL) ./config.status


mostlyclean-noinstLIBRARIES:

clean-noinstLIBRARIES:
	-test -z "$(noinst_LIBRARIES)" || rm -f $(noinst_LIBRARIES)

distclean-noinstLIBRARIES:

maintainer-clean-noinstLIBRARIES:

.s.o:
	$(COMPILE) -c $<

.S.o:
	$(COMPILE) -c $<

mostlyclean-compile:
	-rm -f *.o core *.core

clean-compile:

distclean-compile:
	-rm -f *.tab.c

maintainer-clean-compile:

libposergzip.a: $(libposergzip_a_OBJECTS) $(libposergzip_a_DEPENDENCIES)
	-rm -f libposergzip.a
	$(AR) cru libposergzip.a $(libposergzip_a_OBJECTS) $(libposergzip_a_LIBADD)
	$(RANLIB) libposergzip.a

tags: TAGS

ID: $(HEADERS) $(SOURCES) $(LISP)
	list='$(SOURCES) $(HEADERS)'; \
	unique=`for i in $$list; do echo $$i; done | \
	  awk '    { files[$$0] = 1; } \
	       END { for (i in files) print i; }'`; \
	here=`pwd` && cd $(srcdir) \
	  && mkid -f$$here/ID $$unique $(LISP)

TAGS:  $(HEADERS) $(SOURCES)  $(TAGS_DEPENDENCIES) $(LISP)
	tags=; \
	here=`pwd`; \
	list='$(SOURCES) $(HEADERS)'; \
	unique=`for i in $$list; do echo $$i; done | \
	  awk '    { files[$$0] = 1; } \
	       END { for (i in files) print i; }'`; \
	test -z "$(ETAGS_ARGS)$$unique$(LISP)$$tags" \
	  || (cd $(srcdir) && etags $(ETAGS_ARGS) $$tags  $$unique $(LISP) -o $$here/TAGS)

mostlyclean-tags:

clean-tags:

distclean-tags:
	-rm -f TAGS ID

maintainer-clean-tags:

distdir = $(top_builddir)/$(PACKAGE)-$(VERSION)/$(subdir)

subdir = Gzip

distdir: $(DISTFILES)
	here=`cd $(top_builddir) && pwd`; \
	top_distdir=`cd $(top_distdir) && pwd`; \
	distdir=`cd $(distdir) && pwd`; \
	cd $(top_srcdir) \
	  && $(AUTOMAKE) --include-deps --build-dir=$$here --srcdir-name=$(top_srcdir) --output-dir=$$top_distdir --foreign Gzip/Makefile
	@for file in $(DISTFILES); do \
	  d=$(srcdir); \
	  if test -d $$d/$$file; then \
	    cp -pr $$d/$$file $(distdir)/$$file; \
	  else \
	    test -f $(distdir)/$$file \
	    || ln $$d/$$file $(distdir)/$$file 2> /dev/null \
	    || cp -p $$d/$$file $(distdir)/$$file || :; \
	  fi; \
	done

DEPS_MAGIC := $(shell mkdir .deps > /dev/null 2>&1 || :)

-include $(DEP_FILES)

mostlyclean-depend:

clean-depend:

distclean-depend:
	-rm -rf .deps

maintainer-clean-depend:

%.o: %.c
	@echo '$(COMPILE) -c $<'; \
	$(COMPILE) -Wp,-MD,.deps/$(*F).pp -c $<
	@-cp .deps/$(*F).pp .deps/$(*F).P; \
	tr ' ' '\012' < .deps/$(*F).pp \
	  | sed -e 's/^\\$$//' -e '/^$$/ d' -e '/:$$/ d' -e 's/$$/ :/' \
	    >> .deps/$(*F).P; \
	rm .deps/$(*F).pp

%.lo: %.c
	@echo '$(LTCOMPILE) -c $<'; \
	$(LTCOMPILE) -Wp,-MD,.deps/$(*F).pp -c $<
	@-sed -e 's/^\([^:]*\)\.o[ 	]*:/\1.lo \1.o :/' \
	  < .deps/$(*F).pp > .deps/$(*F).P; \
	tr ' ' '\012' < .deps/$(*F).pp \
	  | sed -e 's/^\\$$//' -e '/^$$/ d' -e '/:$$/ d' -e 's/$$/ :/' \
	    >> .deps/$(*F).P; \
	rm -f .deps/$(*F).pp
info-am:
info: info-am
dvi-am:
dvi: dvi-am
check-am: all-am
check: check-am
installcheck-am:
installcheck: installcheck-am
install-exec-am:
install-exec: install-exec-am

install-data-am:
install-data: install-data-am

install-am: all-am
	@$(MAKE) $(AM_MAKEFLAGS) install-exec-am install-data-am
install: install-am
uninstall-am:
uninstall: uninstall-am
all-am: Makefile $(LIBRARIES)
all-redirect: all-am
install-strip:
	$(MAKE) $(AM_MAKEFLAGS) INSTALL_STRIP_FLAG=-s install
installdirs:


mostlyclean-generic:

clean-generic:

distclean-generic:
	-rm -f Makefile $(CONFIG_CLEAN_FILES)
	-rm -f config.cache config.log stamp-h stamp-h[0-9]*

maintainer-clean-generic:
mostlyclean-am:  mostlyclean-noinstLIBRARIES mostlyclean-compile \
		mostlyclean-tags mostlyclean-depend mostlyclean-generic

mostlyclean: mostlyclean-am

clean-am:  clean-noinstLIBRARIES clean-compile clean-tags clean-depend \
		clean-generic mostlyclean-am

clean: clean-am

distclean-am:  distclean-noinstLIBRARIES distclean-compile \
		distclean-tags distclean-depend distclean-generic \
		clean-am

distclean: distclean-am

maintainer-clean-am:  maintainer-clean-noinstLIBRARIES \
		maintainer-clean-compile maintainer-clean-tags \
		maintainer-clean-depend maintainer-clean-generic \
		distclean-am
	@echo "This command is intended for maintainers to use;"
	@echo "it deletes files that may require special tools to rebuild."

maintainer-clean: maintainer-clean-am

.PHONY: mostlyclean-noinstLIBRARIES distclean-noinstLIBRARIES \
clean-noinstLIBRARIES maintainer-clean-noinstLIBRARIES \
mostlyclean-compile distclean-compile clean-compile \
maintainer-clean-compile tags mostlyclean-tags distclean-tags \
clean-tags maintainer-clean-tags distdir mostlyclean-depend \
distclean-depend clean-depend maintainer-clean-depend info-am info \
dvi-am dvi check check-am installcheck-am installcheck install-exec-am \
install-exec install-data-am install-data install-am install \
uninstall-am uninstall all-redirect all-am all installdirs \
mostlyclean-generic distclean-generic clean-generic \
maintainer-clean-generic clean mostlyclean distclean maintainer-clean


# Tell versions [3.59,3.63) of GNU make to not export all variables.
# Otherwise a system limit (for SysV at least) may be exceeded.
.NOEXPORT:
