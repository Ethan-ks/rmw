AC_INIT(rmw, 0.4.01-pre3, [andy400-dev@yahoo.com])
AM_INIT_AUTOMAKE([subdir-objects])
AC_PREREQ(2.69)
AC_CONFIG_HEADERS([src/config.h:src/config.in])
AC_PROG_CC([cc])
AC_CONFIG_MACRO_DIRS([m4])
AC_PROG_LIBTOOL
AC_PROG_INSTALL
AC_HEADER_STDBOOL
AM_PROG_CC_C_O
AC_CHECK_LIB([curses], [initscr])
AC_CHECK_LIB([menu], [new_menu])

AM_GNU_GETTEXT([external], [need-formatstring-macros])
AM_GNU_GETTEXT_VERSION([0.19.8])

AC_OUTPUT(Makefile src/Makefile etc/Makefile man/Makefile po/Makefile.in)
