
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

Please note that the `__ARMCC_VERSION` macro is also used as version indicator for Norcroft C, but that the format is different.

##### Example #####

Realview C|`__ARMCC_VERSION`
---|---
3.0|300503

