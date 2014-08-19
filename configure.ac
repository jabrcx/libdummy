AC_INIT([libdummy], [0.0.1], [john_brunelle@harvard.edu])
AM_INIT_AUTOMAKE([-Wall -Werror foreign])

##if using extra macros
#AC_CONFIG_MACRO_DIR([m4])

AC_PROG_CC

#if building a library
AC_PROG_LIBTOOL
AM_PROG_AR

#AC_CHECK_HEADERS([...])
#AC_CHECK_LIB([...])

AC_CONFIG_HEADERS([config.h])
AC_CONFIG_FILES([
	Makefile
	src/Makefile
])
AC_OUTPUT
