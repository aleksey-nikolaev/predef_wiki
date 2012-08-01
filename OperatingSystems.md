
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
