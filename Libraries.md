
 ## Standard C Libraries ##

### [Bionic libc](http://en.wikipedia.org/wiki/Bionic_%28software%29) ###

Type|Macro
---|---
Idenfication|`__BIONIC__`

### [GNU glibc](http://en.wikipedia.org/wiki/Glibc) ###

The following macros have to be included from the `` header file.

Type|Macro|Description
---|---|---
Version|`__GNU_LIBRARY__``__GNU_LIBRARY_MINOR__`|Until version 5
Version|`__GLIBC__``__GLIBC_MINOR__`|From version 6

Please notice that the `` header file does not exist on all platforms, so it cannot be included without further ado. However, since it is included by other GNU glibc header files, a better way to obtain the above-mentioned macros is to include the `` header file (see e.g. paragraph 4/6 in ISO/IEC 9899:1999).

### [klibc](http://en.wikipedia.org/wiki/Klibc) ###

Type|Macro|Format|Description
---|---|---|---
Identification|`__KLIBC__`| |Zero is a valid value
Version|`__KLIBC__`| |Version
Version|`__KLIBC_MINOR__`| |Revision
Version|`__KLIBC_PATCHLEVEL__`| |Patch
Version|`__KLIBC_VERSION__`|0xVVRRPPPP|VV = VersionRR = RevisionPPPP = Patch

### [uClibc](http://en.wikipedia.org/wiki/Uclibc) ###

The following macros have to be included from the `` header file.

Type|Macro|Description
---|---|---
Identification|`__UCLIBC__`|
Version|`__UCLIBC_MAJOR__`|Version
Version|`__UCLIBC_MINOR__`|Revision
Version|`__UCLIBC_SUBLEVEL__`|Patch

