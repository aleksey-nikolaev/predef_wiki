
 Please send updates/corrections to [predef-contribute](mailto:predef-contribute@lists.sourceforge.net).

## [Alpha](http://en.wikipedia.org/wiki/DEC_Alpha) ##

Type|Macro|Description
---|---|---
Identification|`__alpha__`|Defined by GNU C
Version|`__alpha_ev'V'__`|V = Version
Identification|`__alpha`|Defined by DEC C
Identification|`_M_ALPHA`|Defined by Visual Studio

##### Example #####

CPU|Macro
---|---
Alpha EV4|`__alpha_ev4__`
Alpha EV5|`__alpha_ev5__`
Alpha EV6|`__alpha_ev6__`

## [AMD64](http://en.wikipedia.org/wiki/Amd64) ##

Type|Macro|Description
---|---|---
Identification|`__amd64__``__amd64``__x86_64__``__x86_64`|Defined by GNU C and Sun Studio
Identification|_M_X64`_M_AMD64`|Defined by Visual Studio

## [ARM](http://en.wikipedia.org/wiki/ARM_architecture) ##

Type|Macro|Description
---|---|---
Identification|`__arm__`|Defined by GNU C and RealView
Identification|`__thumb__`|Defined by GNU C and RealView in Thumb mode
Identification|`__TARGET_ARCH_ARM``__TARGET_ARCH_THUMB`|Defined by RealView
Version|`__TARGET_ARCH_ARM` = V`__TARGET_ARCH_THUMB` = V|V = Version
Version|`__TARGET_ARCH_'VR'`|VR = Version and Revision
Identification|`_ARM`|Defined by ImageCraft C
Identification|`_M_ARM`|Defined by Visual Studio
Identification|`_M_ARMT`|Defined by Visual Studio in Thumb mode
Version|`_M_ARM` = V|V = Version

##### Example #####

CPU|Macro|`_M_ARM`
---|---|---
ARM 4T|`__TARGET_ARM_4T`|
ARM 5| |5
ARM 6| |6
ARM 7| |7

## [Convex](http://en.wikipedia.org/wiki/Convex_Computer) ##

Type|Macro|Description
---|---|---
Identification|`__convex__`|Defined by GNU C
Version|`__convex_'V'__`|V = Version

##### Example #####

CPU|Macro
---|---
Convex C1|`__convex_c1__`
Convex C2|`__convex_c2__`
Convex C32xx series|`__convex_c32__`
Convex C34xx series|`__convex_c34__`
Convex C38xx series|`__convex_c38__`

## [HP/PA RISC](http://en.wikipedia.org/wiki/PA-RISC_family) ##

Type|Macro|Description
---|---|---
Identification|`__hppa__`|Defined by GNU C
Identification|`__HPPA__`|Defined by Stratus VOS C
Identification|`__hppa`|
Version|`_PA_RISC'V'_'R'`|V = VersionR = Revision

See also [http://www.openpa.net/ OpenPA.net].

##### Example #####

CPU|Macro
---|---
PA RISC 1.0|`_PA_RISC1_0`
PA RISC 1.1|`_PA_RISC1_1``__HPPA11__``__PA7100__`
PA RISC 2.0|`_PA_RISC2_0``__RISC2_0__``__HPPA20__``__PA8000__`

## [Intel x86](http://en.wikipedia.org/wiki/X86) ##

Type|Macro|Format|Description
---|---|---|---
Identification|`i386``__i386``__i386__`| |Defined by GNU C
Version|`__i386__``__i486__``__i586__``__i686__`| |Defined by GNU C
Identification|`__i386`| |Defined by Sun Studio
Identification|`__i386``__IA32__`| |Defined by Stratus VOS C
Identification|`_M_I86`| |Only defined for 16-bits architecturesDefined by Visual Studio, Digital Mars, and Watcom C/C++ (see note below)
Identification|`_M_IX86`| |Only defined for 32-bits architecturesDefined by Visual Studio, Intel C/C++, Digital Mars, and Watcom C/C++
Version|`_M_IX86`|V00|V = Version
Identification|`__X86__`| |Defined by Watcom C/C++
Identification|`_X86_`| |Defined by MinGW32
Identification|`__THW_INTEL__`| |Defined by XL C/C++
Identification|`__I86__`| |Defined by Digital Mars
Version|`__I86__`|V|V = Version
Identification|`__INTEL__`| |Defined by CodeWarrior

Notice that Watcom C/C++ defines `_M_IX86` for both 16-bits and 32-bits architectures. Use `__386__` or `_M_I386` to detect 32-bits architectures in this case.

Notice that the Stratus VOS is big-endian on IA32, so these macros cannot be used to detect endianness if `__VOS__` is set.

##### Example #####

CPU|`_M_IX86`|`__I86__`
---|---|---
80386|300|3
80486|400|4
Pentium|500|5
Pentium Pro/II|600|6

## [Intel Itanium (IA-64)](http://en.wikipedia.org/wiki/Itanium) ##

Type|Macro|Format|Description
---|---|---|---
Identification|`__ia64__``_IA64``__IA64__`| |Defined by GNU C
Identification|`__ia64`| |Defined by HP aCC
Identification|`_M_IA64`| |Defined by Visual Studio
Identification|`_M_IA64`| |Defined by Intel C/C++
Version|`_M_IA64`|?|
Identification|`__itanium__`| |Defined by Intel C/C++

##### Example #####

CPU|`_M_IA64` (Intel C/C++)
---|---
 |64100

## [ Motorola 68k](http://en.wikipedia.org/wiki/M68k) ##

Type|Macro|Description
---|---|---
Identification|`__m68k__`|Defined by GNU C
Version|`__mc'V'__``__mc'V'``mc'V'`|V = Version
Identification|`M68000`|Defined by SAS/C
Identification|`__MC68K__`|Defined by Stratus VOS C
Version|`__MC'V'__`|V = Version

##### Example #####

CPU|Macro
---|---
68000|`__mc68000__``__MC68000__`
68010|`__mc68010__`
68020|`__mc68020__``__MC68020__`
68030|`__mc68030__``__MC68030__`
68040|`__mc68040__`
68060|`__mc68060__`

## [MIPS](http://en.wikipedia.org/wiki/MIPS_architecture) ##

Type|Macro|Description
---|---|---
Identification|`__mips__``mips`|Defined by GNU C
Version|`_MIPS_ISA` = `_MIPS_ISA_MIPS'V'`|V = MIPS ISA level
Version|`_R3000``_R4000``_R5900`|
Identification|`__mips`|Defined by MIPSpro and GNU C
Version|`__mips`|The value indicates the MIPS ISA (Instruction Set Architecture) level
Version|`__MIPS_ISA'V'__`|V = MIPS ISA level
Identification|`__MIPS__`|Defined by Metrowerks

##### Example #####

CPU|`_MIPS_ISA`|GNU C Macro|`__mips`|MIPSpro Macro
---|---|---|---|---
R2000|`_MIPS_ISA_MIPS1`| |1|
R3000|`_MIPS_ISA_MIPS1`|`_R3000`|1|
R6000|`_MIPS_ISA_MIPS2`| |2|`__MIPS_ISA2__`
R4000| |`_R4000`| |
R4400|`_MIPS_ISA_MIPS3`| |3|`__MIPS_ISA3__`
R8000|`_MIPS_ISA_MIPS4`| |4|`__MIPS_ISA4__`
R10000|`_MIPS_ISA_MIPS4`| |4|`__MIPS_ISA4__`

## [PowerPC](http://en.wikipedia.org/wiki/PowerPC) ##

Type|Macro|Description
---|---|---
Identification|`__powerpc``__powerpc__``__POWERPC__``__ppc__`|Defined by GNU C
Version|`__ppc'V'__`|V = Version
Identification|`_M_PPC`|Defined by Visual Studio
Version|`_M_PPC`|?
Identification|`_ARCH_PPC`|Defined by XL C/C++
Version|`_ARCH_'V'`|V = Version
Version|`__PPCGECKO__`|[Gekko](http://en.wikipedia.org/wiki/Gekko_%28microprocessor%29)Defined by CodeWarrior
Version|`__PPCBROADWAY__`|[Broadway](http://en.wikipedia.org/wiki/Broadway_%28microprocessor%29)Defined by CodeWarrior
Version|`_XENON`|[Xenon](http://en.wikipedia.org/wiki/Xenon_%28processor%29)

##### Example #####

CPU|`_M_PPC`|Macro|XL Macro
---|---|---|---
PowerPC 601|601|`__ppc601__`|`_ARCH_601`
PowerPC 603|603|`__ppc603__`|`_ARCH_603`
PowerPC 604|604|`__ppc604__`|`_ARCH_604`
PowerPC 620|620| |

## Pyramid 9810 ##

Type|Macro
---|---
Identification|`pyr`

## [RS/6000](http://en.wikipedia.org/wiki/RS/6000) ##

Type|Macro|Description
---|---|---
Identification|`__THW_RS6000`|Defined by XL C/C++
Identification|`_IBMR2`|
Identification|`_POWER`|
Identification|`_ARCH_PWR``_ARCH_PWR2``_ARCH_PWR3``_ARCH_PWR4`|

# [SPARC](http://en.wikipedia.org/wiki/SPARC) ##

Type|Macro|Description
---|---|---
Identification|`__sparc__`|Defined by GNU C
Identification|`__sparc`|Defined by Sun Studio
Version|`__sparcv8``__sparcv9`|Defined by Sun Studio

##### Example #####

CPU|Macro
---|---
SPARC v8 (SuperSPARC)|`__sparcv8`
SPARC v9 (UltraSPARC)|`__sparcv9`

## [SuperH](http://en.wikipedia.org/wiki/SuperH) ##

Type|Macro|Description
---|---|---
Identification|`__sh__`|Defined by GNU C
Version|`__sh1__``__sh2__``__sh3__``__SH3__``__SH4__``__SH5__`|

## [System/370](http://en.wikipedia.org/wiki/System/370) ##

Type|Macro|Description
---|---|---
Identification|`__370__``__THW_370__`|Defined by XL C/C++

## [System/390](http://en.wikipedia.org/wiki/System/390) ##

Type|Macro|Description
---|---|---
Identification|`__s390__``__s390x__`|Defined by GNU C

## [TMS320](http://en.wikipedia.org/wiki/Texas_Instruments_TMS320) ##

Type|Macro|Description
---|---|---
Identification|`_TMS320C2XX``__TMS320C2000__`|C2000 series
Identification|`_TMS320C5X``__TMS320C55X__`|C5000 series
Identification|`_TMS320C6X``__TMS320C6X__`|C6000 series

##### Example #####

DSP|Macro
---|---
C28xx|`_TMS320C28X`
C54x|`_TMS320C5XX`
C55x|`__TMS320C55X__`
C6200|`_TMS320C6200`
C6400|`_TMS320C6400`
C6400+|`_TMS320C6400_PLUS`
C6600|`_TMS320C6600`
C6700|`_TMS320C6700`
C6700+|`_TMS320C6700_PLUS`
C6740|`_TMS320C6740`

## TMS470 ##

Type|Macro
---|---
Identification|`__TMS470__`

## [z/Architecture](http://en.wikipedia.org/wiki/Z/Architecture) ##

Type|Macro|Description
---|---
Identification|`__SYSC_ZARCH__`|Defined by Systems/C

