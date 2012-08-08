
 Please send updates/corrections to [predef-contribute](mailto:predef-contribute@lists.sourceforge.net).

## [ACC](http://en.wikipedia.org/wiki/ACC_%28programming_language%29) ##

Type|Macro
---|---
Identification|`_ACC_`

## [Altium MicroBlaze C](http://en.wikipedia.org/wiki/Altium) ##

Type|Macro|Format|Description
---|---|---|---
Identification|`__CMB__`| |
Version|`__VERSION__`|VRRR|V=VersionRRR=Revision
Version|`__REVISION__`|P|P=Patch
Version|`__BUILD__`|VRRRPPP|Build number

##### Example #####

Altium MicroBlaze C|`__VERSION__`|`__REVISION__`|`__BUILD__`
---|---|---|---
1.0r2|1000|2|
1.22.2| | |1022001

## [Altium C-to-Hardware](http://en.wikipedia.org/wiki/Altium) ##

Type|Macro|Format|Description
---|---|---|---
Identification|`__CHC__`| |
Version|`__VERSION__`|VRRR|V=VersionRRR=Revision
Version|`__REVISION__`|P|P=PatchBeta releases set this to -1
Version|`__BUILD__`|VRRRPPP|Build number

##### Example #####

Altium C-to-Hardware|`__VERSION__`|`__REVISION__`|`__BUILD__`
---|---|---|---
2.1r1|2001|1|
1.22.2| | |1022001

## [Amsterdam Compiler Kit](http://en.wikipedia.org/wiki/Amsterdam_Compiler_Kit) ##

Type|Macro
---|---
Identification|`__ACK__`

## [ARM Compiler](http://www.arm.com/products/tools/software-tools/rvds/arm-compiler.php) ##

Type|Macro|Format|Description
---|---|---|---
Identification|`__CC_ARM`| |
Version|`__ARMCC_VERSION`|VRPBBB|V = VersionR = RevisionP = PatchBBB = Build

Notice that the `__ARMCC_VERSION` macro is also used as version indicator for Norcroft C, but that the format is different.

##### Example #####

Realview C|`__ARMCC_VERSION`
---|---
3.0|300503

## [Aztec C](http://en.wikipedia.org/wiki/Aztec_C) ##

Type|Macro|Format|Description
---|---|---|---
Identification|`AZTEC_C``__AZTEC_C__`| |
Version|`__VERSION`|VRR|V = VersionRR = Revision

##### Example #####

Aztec C|`__VERSION`
---|---
5.20|520

## [Borland C++](http://en.wikipedia.org/wiki/C_plus_plus_builder) ##

Type|Macro|Format
---|---|---
Identification|`__BORLANDC__`|
Version|`__BORLANDC__`|?
Identification|`__CODEGEARC__`|
Version|`__CODEGEARC__`|?

##### Example #####

Borland C++|C++ Builder|`__BORLANDC__`|`__CODEGEARC__`
---|---|---|---
2.0| |0x200|
3.0| |0x400|
3.1| |0x410|
4.0| |0x452|
5.0| |0x500|
5.02|1.0|0x520|
 |3.0|0x530|
 |4.0|0x540|
5.5|5.0|0x550|
5.51| |0x551|
5.6.4| |0x562|
 |2009|0x613|0x613
 |2010|0x621|0x621

## [CC65](http://en.wikipedia.org/wiki/Cc65) ##

Type|Macro|Format|Description
---|---|---|---
Identification|`__CC65__`| |
Version|`__CC65__`|0xVRP|V = VersionR = RevisionP = Patch

##### Example #####

Version|`__CC65__`
---|---
2.10.1|0x2A1

## [Clang](http://en.wikipedia.org/wiki/Clang) ##

Type|Macro|Format
---|---|---
Identification|`__clang__`|
Version|`__clang_major__`|Version
Version|`__clang_minor__`|Revision
Version|`__clang_patchlevel__`|Patch

Notice that clang also defines the GNU C version macros, but you should use the clang [feature checking macros](http://clang.llvm.org/docs/LanguageExtensions.html#feature_check) to detect the availability of various features.

## [Comeau C++](http://en.wikipedia.org/wiki/Comeau_C/C%2B%2B) ##

Type|Macro|Format|Description
---|---|---|---
Identification|`__COMO__`|
Version|`__COMO_VERSION__`|VRR|V = VersionRR = Revision

##### Example #####

Comeau C++|`__COMO_VERSION__`
---|---
2.3|230

## [Compaq C/C++](http://www.openvms.compaq.com/openvms/brochures/deccplus/) ##

Type|Macro|Format|Description
---|---|---|---
Identification|`__DECC`| |C compiler
Version|`__DECC_VER`|VVRRTPPPP|VV = VersionRR = RevisionT = Type (9 = official)PPPP = Patch
Identification|`__DECCXX`| |C++ compiler
Version|`__DECCXX_VER`|As __DECC_VER|
Identification|`__VAXC`| |Obsolete
Identification|`VAXC`| |Obsolete

##### Example #####

Compaq C/C++|`__DECC_VER`
---|---
6.0-001|60090001

## [Convex C](http://en.wikipedia.org/wiki/Convex_Computer) ##

Type|Macro
---|---
Identification|`__convexc__`

## Cray C ##

Type|Macro|Description
---|---|---
Identification|`_CRAYC`|
Version|`_RELEASE`|Version
Version|`_RELEASE_MINOR`|Revision

## [Diab C/C++](http://www.windriver.com/products/development_suite/wind_river_compiler/) ##

Type|Macro|Format|Description
---|---|---|---
Identification|`__DCC__`|1|
Version|`__VERSION_NUMBER__`|VRPP|V = VersionR = RevisionPP = Patch

##### Example #####

Diab C/C++|`__VERSION_NUMBER__`
---|---
4.4g|4426

## [DICE C](http://en.wikipedia.org/wiki/DICE_%28compiler%29) ##

Type|Macro
---|---
Identification|`_DICE`

## [Digital Mars](http://en.wikipedia.org/wiki/Digital_Mars) ##

Type|Macro|Format|Description
---|---|---|---
Identification|`__DMC__`| |
Version|`__DMC__`|0xVRP|V = VersionR = RevisionP = Patch

##### Example #####

Digital Mars|`__DMC__`
---|---
7.0|0x700
7.2|0x720
8.0|0x800

## [Dignus Systems/C++](http://www.dignus.com/dcxx/) ##

Type|Macro|Format|Description
---|---|---|---
Identification|`__SYSC__`| |
Version|`__SYSC_VER__`|VRRPP|V = VersionRR = RevisionPP = Patch

##### Example #####

Systems/C|`__SYSC_VER__`
---|---
1.80.32|18032

## [DJGPP](http://en.wikipedia.org/wiki/Djgpp) ##

Type|Macro|Description
---|---|---
Identification|`__DJGPP__`|
Version|`__DJGPP__`|Version
Version|`__DJGPP_MINOR__`|Revision
Identification|`__GO32__`|Defined by DJGPP 1.x

##### Example #####

DJGPP|`__DJGPP__`|`__DJGPP_MINOR__`
---|---|---
2.01|2|1

## [EKOPath](http://en.wikipedia.org/wiki/PathScale) ##

Type|Macro|Description
---|---|---
Identification|`__PATHCC__`|
Version|`__PATHCC__`|Version
Version|`__PATHCC_MINOR__`|Revision
Version|`__PATHCC_PATCHLEVEL__`|Patch

##### Example #####

EKOPath|`__PATHCC__`|`__PATHCC_MINOR__`|`__PATHCC_PATCHLEVEL__`
---|---|---|---
2.0|2|0|0

## [EDG C++ Frontend](http://en.wikipedia.org/wiki/Edison_Design_Group) ##

Type|Macro|Format|Description
---|---|---|---
Identification|`__EDG__`| |
Version|`__EDG_VERSION__`|VRR|V = VersionRR = Revision

##### Example #####

EDG C++|`__EDG_VERSION__`
---|---
2.30|230

