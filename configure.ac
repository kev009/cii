#                                               -*- Autoconf -*-
# Process this file with autoconf to produce a configure script.

AC_PREREQ([2.61])

AC_INIT([libcii],[2.0],[kevin.bowling@kev009.com])

AC_CONFIG_AUX_DIR([build-aux])
AM_INIT_AUTOMAKE([foreign -Wall -Werror])
LT_PREREQ([2.2])
AC_CONFIG_MACRO_DIR([m4])

# Don't look for C++ or Fortran compilers

m4_undefine([AC_PROG_F77])
m4_defun([AC_PROG_F77],[])

LT_INIT
AC_SUBST(LIBTOOL_DEPS)

AC_CONFIG_SRCDIR([src/text.c])
AC_CONFIG_HEADERS([config.h])

# Checks for programs.
AC_PROG_CC

# Checks for libraries.

# Checks for header files.
AC_CHECK_HEADERS([float.h limits.h stddef.h stdlib.h string.h sys/time.h])

# Checks for typedefs, structures, and compiler characteristics.
AC_TYPE_SIZE_T

# Checks for library functions.
AC_FUNC_MALLOC
AC_FUNC_REALLOC
AC_CHECK_FUNCS([memchr memmove memset strchr strerror])

AC_CONFIG_FILES([Makefile src/Makefile include/Makefile examples/Makefile
misc/Makefile])

AC_OUTPUT
