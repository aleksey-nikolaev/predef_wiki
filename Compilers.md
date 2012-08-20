
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

## [GCC C/C++](http://en.wikipedia.org/wiki/GNU_Compiler_Collection) ##

Type|Macro|Description
---|---|---
Identification|`__GNUC__`|
Version|`__GNUC__`|Version
Version|`__GNUC_MINOR__`|Revision
Version|`__GNUC_PATCHLEVEL__`|Patch (introduced in version 3.0)

Notice that the meaning of the `__GNUC__` macro has changed subtly over the years, from identifying the GNU C/C++ compiler to identifying any compiler that implements the GNU compiler extensions (see the [Feature request - a macro defined for GCC](http://gcc.gnu.org/ml/gcc/2008-07/threads.html#00025) discussion for further information). For example, the Intel C++ on Linux also defines these macros from version 8.1 (see the [Intel C++ Compiler 8.1 for Linux Release Notes](ftp://download.intel.com/support/performancetools/c/linux/sb/clin81_relnotes.pdf) and [Intel Compilers for Linux: Compatibility with GNU Compilers](http://www.intel.com/cd/software/products/asmo-na/eng/284736.htm).)

##### Example #####

GNU C/C++|`__GNUC__`|`__GNUC_MINOR__`|`__GNUC_PATCHLEVEL__`
---|---|---|---
2.7.x|2|7|N/A
3.0.2|3|0|2

### Alternative Version ###

If you prefer a single version macro, you can define the following yourself.

    :::c
    #if defined(__GNUC__)
    # if defined(__GNUC_PATCHLEVEL__)
    #  define __GNUC_VERSION__ (__GNUC__ * 10000 \
                                + __GNUC_MINOR__ * 100 \
                                + __GNUC_PATCHLEVEL__)
    # else
    #  define __GNUC_VERSION__ (__GNUC__ * 10000 \
                                + __GNUC_MINOR__ * 100)
    # endif
    #endif

The format of this new macro is:

Type|Macro|Format|Description
---|---|---|---
Version|`__GNUC_VERSION__`|VVRRPP|VV = VersionRR = RevisionPP = Patch

##### Example of Alternative Version #####

GNU C/C++|`__GNUC_VERSION__`
---|---
2.7.x|20700
3.0.2|30002

## [Green Hill C/C++](http://en.wikipedia.org/wiki/Green_Hills_Software) ##

Type|Macro|Format|Description
---|---|---|---
Identification|`__ghs__`| |
Version|`__GHS_VERSION_NUMBER__`|VRP|V = VersionR = RevisionP = Patch
Version|`__GHS_REVISION_DATE__`|[Epoch time](http://en.wikipedia.org/wiki/Epoch_time)|

##### Example #####

Green Hill C/C++|`__GHS_VERSION_NUMBER__`
---|---
4.2.1|421

## HP ANSI C ##

Type|Macro
---|---
Identification|`__HP_cc`

## [HP aC++](http://en.wikipedia.org/wiki/HP_aC%2B%2B) ##

Type|Macro|Format|Description
---|---|---|---
Identification|`__HP_aCC`| |
Version|`__HP_aCC`|1|From version A.01.15 (and A.03.13)
Version|`__HP_aCC`|VVRRPP|VV = VersionRR = RevisionPP = PatchFrom version A.01.21 (and A.03.25)

##### Example #####

HP aCC|`__HP_aCC`
---|---
A.01.21|012100

### IAR C/C++ ###

Type|Macro|Format|Description
---|---|---|---
Identification|`__IAR_SYSTEMS_ICC__`| |
Version|`__VER__`|VRR|V = VersionRR = Revision

##### Example #####

IAR C/C++|`__VER__`
---|---
3.34|334

## [IBM XL C/C++](http://en.wikipedia.org/wiki/VisualAge) ##

Type|Macro|Format|Description
---|---|---|---
Identification|`__xlc__`| |Compiles C
Identification|`__xlC__`| |Compiles C++
Version|`__xlc__``__xlC__`|0xVVRR|VV = VersionRR = Revision
Identification|`__IBMC__`| |From ?
Identification|`__IBMCPP__`| |From ?
Version|`__IBMC__``__IBMCPP__`|VRP|V = VersionR = RevisionP = Patch

Notice that the z/OS C/C++ compiler also defines `__IBMC__` and `__IBMCPP__` macros, but with a different syntax. See the entry on the z/OS C/C++ compiler below for further information.

##### Example #####

IBM XL C/C++|`__xlC__`|`__IBMCPP__`
---|---|---
3.1|0x0301|
4.5|0x0405|450
5.0|0x0500|500

## [IBM z/OS C/C++](http://en.wikipedia.org/wiki/VisualAge) ##

This is the XL C/C++ compiler for mainframes (e.g. z/OS). The entry on XL C/C++ has been split into two for clarity.

Type|Macro|Format|Description
---|---|---|---
Identification|`__IBMC__`| |
Identification|`__IBMCPP__`| |
Version|`__IBMC__``__IBMCPP__`|NVRRM|N = Product (0 = C/370, 1 = MVS, 2 = OS/390, 4 = z/OS)V = VersionRR = RevisionP = PatchDefined for z/OS XL C/C++
Version|`__COMPILER_VER__`|0xNVRRPPPP|N = Product (see above)V = VersionRR = RevisionPPPP = PatchDefined for z/OS XL C/C++

Notice that XL C/C++ also defines `__IBMC__` and `__IBMCPP__` macros, but with a different syntax. You can use `__xlC__` (only defined for XL C/C++) or `__COMPILER_VER__` (only defined for z/OS C/C++) to distinguish between the two.

    :::c
    #if defined(__IBMC__) || defined(__IBMCPP__)
    # if defined(__COMPILER_VER__)
    /* z/OS C/C++ so __IBMC__ is defined as NVRRM */
    # else
    /* XL C/C++ so __IBMC__ is defined as VRP */
    # endif
    #endif

##### Example #####

IBM z/OS XL C/C++|`__IBMC__`|`__COMPILER_VER__`
---|---|---
1.7|41070|0x41070000

## [ImageCraft C](http://www.imagecraft.com/) ##

Type|Macro
---|---
Identification|`__IMAGECRAFT__`

## [Intel C/C++](http://en.wikipedia.org/wiki/Intel_C%2B%2B) ##

Type|Macro|Format|Description
---|---|---|---
Identification|`__INTEL_COMPILER`| |
Identification|`__ICC`| |Obsolete
Identification|`__ECC`| |Obsolete
Identification|`__ICL`| |
Version|`__INTEL_COMPILER`|VRP|V = VersionR = RevisionP = Patch
Version|`__INTEL_COMPILER_BUILD_DATE`|YYYYMMDD|YYYY = YearMM = MonthDD = Day

##### Example #####

Intel C/C++|`__INTEL_COMPILER`|`__INTEL_COMPILER_BUILD_DATE`
---|---|---
5.0|500|
6.0|600|
8.0|800|
9.0|900|20060222

## KAI C++ ##

Type|Macro|Format|Description
---|---|---|---
Identification|`__KCC`| |
Version|`__KCC_VERSION`|0xVRPP|V = VersionR = RevisionPP = Patch (a = 01, b = 02, ...)

##### Example #####

KAI C++|`__KCC_VERSION`
---|---
4.0d|4004

## [KEIL CARM](http://www.keil.com/arm/carm.asp) ##

Type|Macro|Format|Description
---|---|---|---
Identification|`__CA__`| |
Identification|`__KEIL__`| |
Version|`__CA__`|VRR|V = VersionRR = Revision

##### Example #####

Keil CARM|`__CA__`
---|---
1.01|101

## [KEIL C166](http://www.keil.com/c166/c166.asp) ##

Type|Macro|Format|Description
---|---|---|---
Identification|`__C166__`| |
Version|`__C166__`|VRR|V = VersionRR = Revision

##### Example #####

Keil C166|`__C166__`
---|---
5.01|501

## [KEIL C51](http://www.keil.com/c51/c51.asp) ##

Type|Macro|Format|Description
---|---|---|---
Identification|`__C51__`| |
Identification|`__CX51__`| |
Version|`__C51__`|VRR|V = VersionRR = Revision

##### Example #####

Keil C51|`__C51__`
---|---
7.01|701

## [LCC](http://en.wikipedia.org/wiki/Local_C_compiler) ##

Type|Macro
---|---
Identification|`__LCC__`

## [LLVM](http://en.wikipedia.org/wiki/LLVM) ##

Type|Macro
---|---
Identification|`__llvm__`

## MetaWare High C/C++ ##

Type|Macro
---|---
Identification|`__HIGHC__`

## [Metrowerks CodeWarrior](http://en.wikipedia.org/wiki/CodeWarrior) ##

Type|Macro|Format|Description
---|---|---|---
Identification|`__MWERKS__`| |
Identification|`__CWCC__`| |From 4.2.0
Version|`__MWERKS__`|1|Until CodeWarrior 7
Version|`__MWERKS__`|0xVRPP|V = VersionR = RevisionPP = PatchFrom CodeWarrior 7
Version|`__CWCC__`|0xVRPP|V = VersionR = RevisionPP = PatchFrom 4.2.0

##### Example #####

Metrowerks C/C++|`__MWERKS__`|`__CWCC__`
---|---|---
2.0|0x2000|
2.2|0x2200|
4.2.0|0x4200|0x4200

## [Microsoft Visual C++](http://en.wikipedia.org/wiki/Visual_studio) ##

Type|Macro|Format|Description
---|---|---|---
Identification|`_MSC_VER`| |
Version|`_MSC_VER`|VVRR|VV = VersionRR = Revision
Version|`_MSC_FULL_VER`|VVRRPPPP|VV = VersionRR = RevisionPPPP = PatchFrom ?
Version|`_MSC_FULL_VER`|VVRRPPPPP|VV = VersionRR = RevisionPPPPP = PatchFrom Visual C++ 8.0
Version|`_MSC_BUILD`|B|B = Build numberFrom Visual C++ 9.0

##### Example #####

Visual C++|`_MSC_VER`|`_MSC_FULL_VER`
---|---|---
1.0|800|
3.0|900|
4.0|1000|
4.2|1020|
5.0|1100|
6.0|1200|
6.0 SP6|1200|12008804
7.0|1300|13009466
7.1 (2003)|1310|13103077
8.0 (2005)|1400|140050727
9.0 (2008)|1500|150021022
10.0 (2010)|1600|160040219

## [Microtec C/C++](http://www.mentor.com/microtec/) ##

Type|Macro
---|---
Identification|`_MRI`

## [Microway NDP C](http://en.wikipedia.org/wiki/Microway) ##

Type|Macro
---|---
Identification|`__NDPC__``__NDPX__`

## [MinGW](http://www.mingw.org/) and [MinGW-w64](http://mingw-w64.sourceforge.net/) ##

MinGW (formerly known as MinGW32) is a toolchain for creating 32 Bit Windows executables. The MinGW-w64 projects offers toolchains for creating 32 Bit and 64 Bit Windows executables. The following table shows which macros are defined by each toolchain:

Type|Macro|Description|MinGW32|MinGW-w64 32 Bit|MinGW-w64 64 Bit
---|---|---|---|---|---
Identification|`__MINGW32__`| | defined | defined | defined
Version|`__MINGW32_MAJOR_VERSION`|Version| defined | defined | defined
Version|`__MINGW32_MINOR_VERSION`|Revision| defined | defined | defined
Identification|`__MINGW64__`| | - | - | defined
Version|`__MINGW64_VERSION_MAJOR`|Version| - | defined | defined
Version|`__MINGW64_VERSION_MINOR`|Revision| - | defined | defined

Please note that `__MINGW32_MAJOR_VERSION`, `__MINGW32_MINOR_VERSION`, `__MINGW64_VERSION_MAJOR`, and `__MINGW64_VERSION_MINOR`
are only defined if appropriate headers are included. Appropriate headers are 
``, ``, ``, ``, and probably more.

##### Examples #####

`__MINGW32_MAJOR_VERSION`|`__MINGW32_MINOR_VERSION`|`__MINGW64_VERSION_MAJOR`|`__MINGW64_VERSION_MINOR`|Description
---|---|---|---|---
2|4| | | MinGW32 2.4
3|20| | | MinGW32 3.20
3|11|2|0| MinGW-w64 2.0

## [MIPSpro](http://en.wikipedia.org/wiki/MIPSpro) ##

Type|Macro|Format|Description
---|---|---|---
Identification|`__sgi`| |
Identification|`sgi`| |
Version|`_COMPILER_VERSION`|VRP|V = VersionR = RevisionP = PatchUntil ?
Version|`_SGI_COMPILER_VERSION`|VRP|V = VersionR = RevisionP = PatchFrom ?

##### Example #####

MIPSpro|`_COMPILER_VERSION`|`_SGI_COMPILER_VERSION`
---|---|---
6.0.2|602|
7.2.1|721|
7.4.4| |744

## [Miracle C](http://www.c-compiler.com/) ##

Type|Macro
---|---
Identification|`MIRACLE`

## [MPW C++](http://en.wikipedia.org/wiki/Macintosh_Programmer%27s_Workshop) ##

Type|Macro|Format|Description
---|---|---|---
Identification|`__MRC__`| |
Identification|`MPW_C`| |
Identification|`MPW_CPLUS`| |
Version|`__MRC__`|0xVVRR|VV = VersionRR = Revision

##### Example #####

MPW C++|`__MRC__`
---|---
5.0|0x500

## [Norcroft C](http://www.codemist.co.uk/ncc/index.html) ##

Type|Macro|Format|Description
---|---|---|---
Identification|`__CC_NORCROFT`| |
Version|`__ARMCC_VERSION`|V.R|V = VersionR = Revision

Please note that `__ARMCC_VERSION` is assigned a floating-point number, so it cannot be used by the preprocessor to compare versions.

##### Example #####

Norcroft C|`__ARMCC_VERSION`
---|---
4.69|4.69
4.90|4.90

## [NWCC](http://nwcc.sourceforge.net/) ##

Type|Macro
---|---
Identification|`__NWCC__`

## [Open64](http://en.wikipedia.org/wiki/Open64) ##

Type|Macro
---|---
Identification|`__OPEN64__`

## Pacific C ##

Type|Macro
---|---
Identification|`__PACIFIC__`

## Palm C/C++ ##

Type|Macro|Format|Description
---|---|--|---
Identification|`_PACC_VER`| |
Version|`_PACC_VER`|0xVRRPPBBB|V = VersionRR = RevisionPP = PatchBBB = Build

##### Example #####

Palm C/C++|`_PACC_VER`
---|---
1.0.0.13|0x1000000D

## [Pelles C](http://en.wikipedia.org/wiki/Pelles_C) ##

Type|Macro|Format|Description
---|---|---|---
Identification|`__POCC__`| |
Version|`__POCC__`|VRR|V = VersionRR = Revision

##### Example #####

Pelles C|`__POCC__`
---|---
3.00|300

## [Portland Group C/C++](http://en.wikipedia.org/wiki/The_Portland_Group) ##

Type|Macro|Description
---|---|---
Identification|`__PGI`|
Version|`__PGIC__`|Version
Version|`__PGIC_MINOR__`|Revision
Version|`__PGIC_PATCHLEVEL__`|Patch

##### Example #####

PGI C/C++|`__PGIC__`|`__PGIC_MINOR__`|`__PGIC_PATCHLEVEL__`
---|---|---|---
7.0.1|7|0|1
11.9|11|9|0

## Renesas C/C++ ##

Type|Macro|Format|Description
---|---|---|---
Identification|`__RENESAS__`| |
Identification|`__HITACHI__`| |
Version|`__RENESAS_VERSION__`|0xVVRR|V = VersionR = RevisionP = Patch
Version|`__RENESAS_VERSION__`|0xVVRRPP00|From ?
Version|`__HITACHI_VERSION__`|0xVVRR|As above

##### Example #####

Renesas C/C++|`__HITACHI_VERSION__`|`__RENESAS_VERSION__`
---|---|---
5.1C|0x0501|
8.0|0x8000|0x8000
1.00.00| |0x01000000

## [SAS/C](http://www.sas.com/products/sasc/) ##

Type|Macro|Format|Description
---|---|---|---
Identification|`SASC`| |
Identification|`__SASC`| |
Identification|`__SASC__`| |
Version|`__VERSION__`| |Until ?
Version|`__REVISION__`| |Until ?
Version|`__SASC__`|VRR|V = VersionRR = RevisionFrom ?

##### Example #####

SAS/C|`__SASC__`|`__VERSION__`|`__REVISION__`
---|---|---|---
5.10| |5|10
6.50|650| |

