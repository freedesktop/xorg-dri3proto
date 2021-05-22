AC_PREREQ([2.60])
AC_INIT([DRI3Proto], [1.0], [https://github.com/freedesktop/xorg-dri3proto])
AM_INIT_AUTOMAKE([foreign dist-bzip2])

# Require xorg-macros: XORG_DEFAULT_OPTIONS
m4_ifndef([XORG_MACROS_VERSION],
          [m4_fatal([must install xorg-macros 1.3 or later before running autoconf/autogen])])
XORG_MACROS_VERSION(1.3)
XORG_DEFAULT_OPTIONS

AC_CONFIG_FILES([Makefile
           dri3proto.pc])
AC_OUTPUT
