AC_INIT(
	[Evergro-backgrounds ],
	1.0,
	[https://github.com/igor-dyatlov/evergro-backgrounds],
	[evergro-backgrounds]
)

AM_INIT_AUTOMAKE([-Wno-portability no-dist-gzip dist-xz foreign subdir-objects 1.9 tar-ustar])
AC_PREFIX_DEFAULT(/usr)
AM_SILENT_RULES([yes])

AC_CONFIG_FILES([ \
	Makefile \
	backgrounds/Makefile ])
AC_OUTPUT

AC_MSG_RESULT([
        Evergro-backgrounds $VERSION
        ===========================================================

         prefix:                 ${prefix}
         datarootdir:            ${datarootdir}
         target directories:     ${datarootdir}/backgrounds/evergro

        ===========================================================
                             =>> run 'make' and 'sudo make install'
])
