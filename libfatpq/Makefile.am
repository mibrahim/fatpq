bin_PROGRAMS=fatpq
fatpq_SOURCES=fatpq.c fatpq.1 xmalloc.c system.h aclocal.m4 getopt.c getopt1.c getopt.h

#  uncomment the following if fatpq requires the math library
#fatpq_LDADD=-lm

EXTRA_DIST=fatpq.lsm.in fatpq.spec.in fatpq.texinfo

#  if you write a self-test script named `chk', uncomment the
#  following and add `chk' to the EXTRA_DIST list
#TESTS=chk

#  build and install the .info pages
info_TEXINFOS = fatpq.texinfo
fatpq_TEXINFOS = gpl.texinfo

#  install the man pages
man_MANS=fatpq.1
