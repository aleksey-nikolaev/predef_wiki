
 ## [AIX](http://en.wikipedia.org/wiki/AIX_operating_system) ##

Type|Macro|Description
---|---|---
Identification|`_AIX`|
Version|`_AIX'VR'`|V = VersionR = Revision
Identification|`__TOS_AIX__`|Defined by xlC

##### Example #####

If `_AIX` is defined, then the following macros can be used to determine the version. Please note that the macros indicates the mentioned version or higher. For example, if `_AIX43` is defined, then `_AIX41` will also be defined.

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

Please notice that Android is based on Linux, and that the Linux macros also are defined for Android.

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

## [GNU Hurd](http://en.wikipedia.org/wiki/GNU/Hurd) ##

Type|Macro
---|---
Identification|`__GNU__`

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

## [Linux](http://en.wikipedia.org/wiki/Linux) ##

Type|Macro|Description
---|---|---
Identification|`__linux__`|
Identification|`linux`|Obsolete
Identification|`__linux`|Obsolete

## [LynxOS](http://en.wikipedia.org/wiki/LynxOS) ##

Type|Macro
---|---
Identification|`__Lynx__`

## [MacOS](http://en.wikipedia.org/wiki/Mac_OS) ##

Type|Macro|Description
---|---|---
Identification|`macintosh`|Mac OS 9
Identification|`Macintosh`|Mac OS 9
Identification|`__APPLE__` & `__MACH__`|Mac OS XDefined by GNU C and Intel C++

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

