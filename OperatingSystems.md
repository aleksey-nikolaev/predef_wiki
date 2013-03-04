
 Please send updates/corrections to [predef-contribute](mailto:predef-contribute@lists.sourceforge.net).

## [AIX](http://en.wikipedia.org/wiki/AIX_operating_system) ##

Type|Macro|Description
---|---|---
Identification|`_AIX`|
Version|`_AIX'VR'`|V = VersionR = Revision
Identification|`__TOS_AIX__`|Defined by xlC

##### Example #####

If `_AIX` is defined, then the following macros can be used to determine the version. Notice that the macros indicates the mentioned version or higher. For example, if `_AIX43` is defined, then `_AIX41` will also be defined.

AIX Version|Macro
--|---
3.2.x|`_AIX3``_AIX32`
4.1|`_AIX41`
4.3|`_AIX43`

## [Android](http://en.wikipedia.org/wiki/Android_%28operating_system%29) ##

Type|Macro|Format|Description
---|---|---|--
Identification|`__ANDROID__`| |
Version|`__ANDROID_API__`|V|V = API VersionMust be included from ``

Notice that Android is based on Linux, and that the Linux macros also are defined for Android.

##### Example #####

Android Version|`__ANDROID_API__`
---|---
1.0|1
1.1|2
1.5|3
1.6|4
2.0|5
2.0.1|6
2.1|7
2.2|8
2.3|9
2.3.3|10
3.0|11

## [Amdahl UTS](http://en.wikipedia.org/wiki/UTS_%28Mainframe_UNIX%29) ##

Type|Macro
---|---
Identification|`UTS`

## [AmigaOS](http://en.wikipedia.org/wiki/AmigaOS) ##

Type|Macro|Description
---|---|---
Identification|`AMIGA`|
Identification|`__amigaos__`|Defined by GNU C

## [Apollo AEGIS](http://en.wikipedia.org/wiki/Domain/OS) ##

Type|Macro
--|---
Identification|`aegis`

## [Apollo Domain/OS](http://en.wikipedia.org/wiki/Domain/OS) ##

Type|Macro
---|---
Identification|`apollo`

## [Bada](http://en.wikipedia.org/wiki/Bada_%28operating_system%29) ##

Based on Nucleus OS.

## [BeOS](http://en.wikipedia.org/wiki/BeOS) ##

Type|Macro
---|---
Identification|`__BEOS__`

## [Blue Gene](http://en.wikipedia.org/wiki/Bluegene) ##

Type|Macro|Description
---|---|---
Identification|`__bg__`|Defined for XL C/C++

## [BSD Environment](http://en.wikipedia.org/wiki/Bsd) ##

Type|Macro|Format|Description
---|---|---|---
Identification|`__FreeBSD__``__NetBSD__``__OpenBSD__``__bsdi__``__DragonFly__`| |
Version|`BSD`|YYYYMM|YYYY = YearMM = MonthMust be included from ``
Version|`BSD4_2``BSD4_3``BSD4_4`| |Must be included from ``
Identification|`_SYSTYPE_BSD`| |Defined by DEC C

##### Example #####

Version|`BSD`|Macro
---|---|--
4.3 Net2|199103|
4.4|199306|`BSD4_4`
4.4BSD-Lite2|199506|

## [BSD/OS](http://en.wikipedia.org/wiki/BSD/OS) ##

Type|Macro
---|---
Identification|`__bsdi__`

## [ConvexOS](http://en.wikipedia.org/wiki/Convex_Computer) ##

Type|Macro
---|---
Identification|`__convex__`

## [Cygwin Environment](http://en.wikipedia.org/wiki/Cygwin) ##

Type|Macro
---|---
Identification|`__CYGWIN__`

## [DG/UX](http://en.wikipedia.org/wiki/Data_General) ##

Type|Macro
---|---
Identification|`DGUX`
Identification|`__DGUX__`
Identification|`__dgux__`

## [DragonFly](http://en.wikipedia.org/wiki/DragonFly_BSD) ##

Type|Macro
---|---
Identification|`__DragonFly__`

## [DYNIX/ptx](http://en.wikipedia.org/wiki/Dynix) ##

Type|Macro
---|---
Identification|`_SEQUENT_`
Identification|`sequent`

## [eCos](http://en.wikipedia.org/wiki/ECos) ##

Type|Macro
---|---
Identification|`__ECOS`

## [EMX Environment](http://en.wikipedia.org/wiki/EMX_%28programming_environment%29) ##

Type|Macro
---|---
Identification|`__EMX__`

## [FreeBSD](http://en.wikipedia.org/wiki/Freebsd) ##

Type|Macro|Format|Description
---|---|---|---
Identification|`__FreeBSD__`| |
Identification|`__FreeBSD_kernel__`| |From FreeBSD 8.3, 9.1, and 10.0.[1](http://svnweb.freebsd.org/base/head/sys/sys/param.h?view=markup)
Version|`BSD`| |
Version|`__FreeBSD__`|V|V = Version
Version|`__FreeBSD_version`|?|Must be included from ``

##### Example #####

FreeBSD|`__FreeBSD__`|`__FreeBSD_version`
---|---|---
1.x|1|
2.0-RELEASE|2|119411
2.2-RELEASE|2|220000
3.0-RELEASE|3|300005
4.0-RELEASE|4|400017
4.5-RELEASE|4|450000

For more information see the [FreeBSD porters handbook](http://www.freebsd.org/doc/en_US.ISO8859-1/books/porters-handbook/freebsd-versions.html).

## GNU aka [GNU/Hurd](http://en.wikipedia.org/wiki/GNU/Hurd) ##

The official name of this operating system is GNU.  Hurd is the kernel in the GNU operating system.  It is often listed as GNU/Hurd since there is also GNU/Linux and GNU/kFreeBSD, which are most of the GNU operating system with the Linux and FreeBSD kernels respectively.

Type|Macro
---|---
Identification|`__GNU__` [1](http://gcc.gnu.org/viewcvs/trunk/gcc/config/gnu.h?view=markup)
Identification|`__gnu_hurd__` [1](http://gcc.gnu.org/viewcvs/trunk/gcc/config/gnu.h?view=markup)

## [GNU/kFreeBSD](http://en.wikipedia.org/wiki/GNU/kFreeBSD) ##

GNU/kFreeBSD is one of the Debian distros that is based on the FreeBSD kernel rather than the Linux or Hurd kernels.

Type|Macro
---|---
Identification|`__FreeBSD_kernel__` `&&` `__GLIBC__`

Notice that FreeBSD also defines `__FreeBSD_kernel__` so the `__GLIBC__` macro must be checked to distinguish it.

## [GNU/Linux](http://en.wikipedia.org/wiki/GNU/Linux) ##

Type|Macro
---|---
Identification|`__gnu_linux__`

## [HI-UX MPP](http://en.wikipedia.org/wiki/HI-UX) ##

Type|Macro
---|---
Identification|`__hiuxmpp`

## [HP-UX](http://en.wikipedia.org/wiki/HP-UX) ##

Type|Macro|Description
---|---|---
Identification|`_hpux`|Defined by HP UPC
Identification|`hpux`|
Identification|`__hpux`|

## [IBM OS/400](http://en.wikipedia.org/wiki/IBM_i) ##

Type|Macro
---|---
Identification|`__OS400__`

## [INTEGRITY](http://en.wikipedia.org/wiki/Integrity_%28operating_system%29) ##

Type|Macro
---|---
Identification|`__INTEGRITY`

## [Interix Environment](http://en.wikipedia.org/wiki/Interix) ##

Type|Macro|Description
---|---|---
Identification|`__INTERIX`|Defined by GNU C and Visual Studio

## [IRIX](http://en.wikipedia.org/wiki/Irix) ##

Type|Macro
---|---
Identification|`sgi`
Identification|`__sgi`

## [Linux kernel](http://en.wikipedia.org/wiki/Linux_kernel) ##

Systems based on the Linux kernel define these macros.  There are two major Linux-based operating systems: [GNU/Linux](http://en.wikipedia.org/wiki/GNU/Linux) and [Android](http://en.wikipedia.org/wiki/Android), and numerous others like [Ångström](http://www.angstrom-distribution.org/) or [OpenEmbedded](http://www.openembedded.org)

Type|Macro|Description
---|---|---
Identification|`__linux__`| [1](http://www.faqs.org/docs/Linux-HOWTO/GCC-HOWTO.html#INDEX.25)
Identification|`linux`|Obsolete (not POSIX compliant)
Identification|`__linux`|Obsolete (not POSIX compliant)

## [LynxOS](http://en.wikipedia.org/wiki/LynxOS) ##

Type|Macro
---|---
Identification|`__Lynx__`

## [MacOS](http://en.wikipedia.org/wiki/Mac_OS) ##

Type|Macro|Description
---|---|---
Identification|`macintosh`|Mac OS 9
Identification|`Macintosh`|Mac OS 9
Identification|`__APPLE__` `&&` `__MACH__`|Mac OS XDefined by GNU C and Intel C++

## [Microware OS-9](http://en.wikipedia.org/wiki/OS-9) ##

Type|Macro|Description
---|---|---
Identification|`__OS9000`|Defined by Ultimate C/C++
Identification|`_OSK`|Defined by Ultimate C/C++

## [MINIX](http://en.wikipedia.org/wiki/Minix) ##

Type|Macro
---|---
Identification|`__minix`

## [MorphOS](http://en.wikipedia.org/wiki/Morphos) ##

Type|Macro
---|---
Identification|`__MORPHOS__`

## [MPE/iX](http://en.wikipedia.org/wiki/MPE) ##

Type|Macro
---|---
Identification|`mpeix`
Identification|`__mpexl`

## [MSDOS](http://en.wikipedia.org/wiki/MS-DOS) ##

Type|Macro
---|---
Identification|`MSDOS`
Identification|`__MSDOS__`
Identification|`_MSDOS`
Identification|`__DOS__`

## [NetBSD](http://en.wikipedia.org/wiki/Netbsd) ##

Type|Macro|Format|Description
---|---|---|---
Identification|`__NetBSD__`| |
Version|`BSD`| |
Version|`NetBSD'V'_'R'`| |V = VersionR = RevisionMust be included from ``
Version|`__NetBSD_Version__`|VVRRAAPP00|VV = VersionRR = RevisionAA = ReleasePP = PatchFrom NetBSD 1.2D (?) until NetBSD 2.0HMust be included from ``
Version|`__NetBSD_Version__`|VVRR00PP00|VV = VersionRR = RevisionPP = PatchFrom NetBSD 2.99.9Must be included from ``

##### Example #####

NetBSD|`__NetBSD_Version__`|Macro
---|---|--
0.8| |`NetBSD0_8`
0.9| |`NetBSD0_9`
1.0| |`NetBSD1_0` = 1
1.0A| |`NetBSD1_0` = 2
1.2D|102040000|
1.2.1|102000100|

## [NonStop](http://en.wikipedia.org/wiki/NonStop) ##

Type|Macro
---|---
Identification|`__TANDEM`

## [Nucleus RTOS](http://en.wikipedia.org/wiki/Nucleus_RTOS) ##

Type|Macro
---|---
Identification|`__nucleus__`

## [OpenBSD](http://en.wikipedia.org/wiki/Openbsd) ##

Type|Macro|Format|Description
---|---|---|---
Identification|`__OpenBSD__`| |
Version|`BSD`| |
Version|`OpenBSD'V'_'R'`| |V = VersionR = RevisionMust be included from ``

##### Example #####

OpenBSD|Macro
---|---
3.1|`OpenBSD3_1`
3.9|`OpenBSD3_9`

## [OS/2](http://en.wikipedia.org/wiki/OS/2) ##

Type|Macro
---|---
Identification|`OS2`
Identification|`_OS2`
Identification|`__OS2__`
Identification|`__TOS_OS2__`

## [Palm OS](http://en.wikipedia.org/wiki/Palmos) ##

Type|Macro|Description
---|---|---
Identification|`__palmos__`|Defined by GNU C in [PRC-Tools](http://prc-tools.sourceforge.net/)

## [Pyramid DC/OSx](http://en.wikipedia.org/wiki/DC/OSx) ##

Type|Macro
---|---
Identification|`pyr`

## [QNX](http://en.wikipedia.org/wiki/QNX) ##

Type|Macro|Format|Description
---|---|---|---
Identification|`__QNX__`| |QNX 4.x
Identification|`__QNXNTO__`| |QNX 6.x
Version|`_NTO_VERSION`|VRR|V = VersionRR = RevisionOnly available when `__QNXNTO__` is defined.Must be included from ``

##### Example #####

QNX|`_NTO_VERSION`
---|---
6.2|620

## [Reliant UNIX](http://en.wikipedia.org/wiki/Reliant_UNIX) ##

Type|Macro
---|---
Identification|`sinux`

## [SCO OpenServer](http://en.wikipedia.org/wiki/SCO_OpenServer) ##

Type|Macro|Description
---|---|---
Identification|`M_I386`|Defined by GNU C
Identification|`M_XENIX`|Defined by GNU C
Identification|`_SCO_DS`|

## [Solaris](http://en.wikipedia.org/wiki/Solaris_Operating_Environment) ##

Type|Macro|Description
---|---|---
Identification|`sun`|
Identification|`__sun`|
Version|`__'System'_'Version'`|System = `uname -s`Version = `uname -r`Any illegal character is replaced by an underscore.Defined by Sun Studio

Use the SVR4 macros to distinguish between Solaris and SunOS.

    :::c
    #if defined(sun) || defined(__sun)
    # if defined(__SVR4) || defined(__svr4__)
    /* Solaris */
    # else
    /* SunOS */
    # endif
    #endif

##### Example #####

Solaris|Macro
---|---
2.7|`__SunOS_5_7`
8 |`__SunOS_5_8`

## [Stratus VOS](http://en.wikipedia.org/wiki/Stratus_VOS) ##

Type|Macro|Format|Description
---|---|---|---
Identification|`__VOS__`| |
Version|`__VOS__`|V|V = Version

Notice that the `__VOS__` macro is defined by the compiler, but as several compilers can co-exist in the same OS release, the version number is not reliable.

## [SVR4 Environment](http://en.wikipedia.org/wiki/UNIX_System_V) ##

Type|Macro|Description
---|---|---
Identification|`__sysv__`|
Identification|`__SVR4`|
Identification|`__svr4__`|
Identification|`_SYSTYPE_SVR4`|Defined on IRIX

## [Syllable](http://en.wikipedia.org/wiki/Syllable_Desktop) ##

Type|Macro
---|---
Identification|`__SYLLABLE__`

## [Symbian OS](http://en.wikipedia.org/wiki/Symbian_OS) ##

Type|Macro
---|---
Identification|`__SYMBIAN32__`

## [Tru64 (OSF/1)](http://en.wikipedia.org/wiki/Digital_UNIX) ##

Type|Macro
---|---
Identification|`__osf__`
Identification|`__osf`

## [Ultrix](http://en.wikipedia.org/wiki/Ultrix) ##

Type|Macro
---|---
Identification|`ultrix`
Identification|`__ultrix`
Identification|`__ultrix__`
Identification|`unix` & `vax`

## [UNICOS](http://en.wikipedia.org/wiki/UNICOS) ##

Type|Macro|Format|Description
---|---|---|---
Identification|`_UNICOS`| |
Version|`_UNICOS`|V|V = Version

## [UNICOS/mp](http://en.wikipedia.org/wiki/Unicos) ##

Type|Macro|Description
---|---|---
Identification|`_CRAY``__crayx1`|

## [UNIX Environment](http://en.wikipedia.org/wiki/Unix) ##

Type|Macro
---|---
Identification|`__unix__`
Identification|`__unix`

Notice that not all compilers defines these macros, e.g. the xlC or the DEC C/C++ compiler, so it may be better to use the POSIX or X/Open standard macros instead.

## [UnixWare](http://en.wikipedia.org/wiki/UnixWare) ##

Type|Macro
---|---
Identification|`sco`
Identification|`_UNIXWARE7`

## [U/Win Environment](http://en.wikipedia.org/wiki/UWIN) ##

Type|Macro
---|---
Identification|`_UWIN`

## [VMS](http://en.wikipedia.org/wiki/Vms) ##

Type|Macro|Format|Description
---|---|---|---
Identification|`VMS`| |
Identification|`__VMS`| |
Version|`__VMS_VER`|VVRREPPTT|VV = VersionRR = RevisionE = Edit numberPP = Patch (01 = A, ... 26 = Z)TT = Type (22 = official)

##### Example #####

VMS|`__VMS_VER`
---|---
6.1|60100022
6.2|60200022
6.2-1I|60210922

## [Windows](http://en.wikipedia.org/wiki/Category:Microsoft_Windows) ##

Type|Macro|Description
---|---|---
Identification|`_WIN16`|Defined for 16-bit environments [1](http://msdn.microsoft.com/en-us/library/ff540443.aspx)
Identification|`_WIN32`|Defined for both 32-bit and 64-bit environments [1](http://msdn.microsoft.com/en-us/library/ff540443.aspx)
Identification|`_WIN64`|Defined for 64-bit environments [1](http://msdn.microsoft.com/en-us/library/ff540443.aspx)
Identification|`__WIN32__`|Defined by Borland C++
Identification|`__TOS_WIN__`|Defined by xlC
Identification|`__WINDOWS__`|Defined by Watcom C/C++

## [Windows CE](http://en.wikipedia.org/wiki/Windows_CE) ##

Type|Macro|Format|Description
---|---|---|---
Identification|`_WIN32_WCE`| |Defined by Embedded Visual Studio C++
Version|`_WIN32_WCE`|VRR|V = VersionR = Revision
Identification|`WIN32_PLATFORM_'P'`| |P = Platform
Version|`WIN32_PLATFORM_'P'`|V|P = PlatformV = Version

##### Example #####

Version|`_WIN32_WCE`
---|---
2.01|201
2.11|211
3.0|300
4.0|400
4.1|410
4.2|420
5.0|501

Platform|Macro|Value
---|---|---
H/PC 2000|`WIN32_PLATFORM_HPC2000`|
H/PC Pro 2.11|`WIN32_PLATFORM_HPCPRO`|211
H/PC Pro 3.0|`WIN32_PLATFORM_HPCPRO`|300
Pocket PC|`WIN32_PLATFORM_PSPC`|1
Pocket PC 2002|`WIN32_PLATFORM_PSPC`|310
Windows Mobile 2003|`WIN32_PLATFORM_PSPC`|400
Smartphone 2002|`WIN32_PLATFORM_WFSP`|100

## [Wind/U Environment](http://en.wikipedia.org/wiki/Bristol_Technology_Inc.) ##

Type|Macro|Format|Description
---|---|---|---
Identification|`_WINDU_SOURCE`| |
Version|`_WINDU_SOURCE`|0xVVRRPP|VV = VersionRR = RevisionPP = Patch

##### Example #####

Wind/U|`_WINDU_SOURCE`
---|---
3.1.2|0x030102

## [z/OS](http://en.wikipedia.org/wiki/Z/OS) ##

Type|Macro|Description
---|---|---
Identification|`__MVS__`|Host
Identification|`__HOS_MVS__`|Host
Identification|`__TOS_MVS__`|Target
