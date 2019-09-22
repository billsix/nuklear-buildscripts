#                                               -*- Autoconf -*-
# Process this file with autoconf to produce a configure script.

AC_PREREQ([2.63])
AC_INIT([libnuklear],[4.1.3], [billsix@gmail.com])
AC_CANONICAL_SYSTEM
AC_CONFIG_MACRO_DIRS([m4])
# Checks for programs.
AM_INIT_AUTOMAKE()
LT_PREREQ([2.4.2])
LT_INIT([disable-static])
AC_PROG_CC
AC_PROG_INSTALL


AC_CONFIG_FILES([Makefile \
        demo/glfw_opengl3/Makefile])


AC_ARG_ENABLE(glfw,
              AC_HELP_STRING([--enable-glfw],
                             [build the GLFW version of nuklear]),
              ENABLE_GLFW=$enableval,
              ENABLE_GLFW=yes)



AC_OUTPUT
