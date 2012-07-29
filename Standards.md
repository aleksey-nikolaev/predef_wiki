
 ## Language Standards ##

Language standards requires the existence of pre-defined macros.

Name | Macro | Standard
---|---|---
C89|\_\_STDC\_\_|ANSI X3.159-1989
C90|\_\_STDC_VERSION\_\_|ISO/IEC 9899:1990
C94|\_\_STDC_VERSION\_\_ = 199409L|ISO/IEC 9899-1:1994
[C99](http://www.open-std.org/jtc1/sc22/wg14/)|\_\_STDC_VERSION\_\_ = 199901L|ISO/IEC 9899:1999
[C11](http://en.wikipedia.org/wiki/C11_%28C_standard_revision%29)|\_\_STDC_VERSION\_\_ = 201112L|ISO/IEC 9899:2011
[C++98](http://www.open-std.org/jtc1/sc22/wg21/)|\_\_cplusplus = 199707L|ISO/IEC 14882:1998
[C++11](http://en.wikipedia.org/wiki/C%2B%2B11)|\_\_cplusplus = 201103L|Draft
[C++/CLI](http://www.ecma-international.org/publications/standards/Ecma-372.htm)|\_\_cplusplus_cli = 200406L|ECMA-372
[DSP-C](http://www.dsp-c.org)| |ISO/IEC JTC1/SC22 WG14/N854
[EC++](http://www.caravan.net/ec2plus/)|\_\_embedded_cplusplus|Embedded C++

##### Example: C Standards #####

    :::c
    #if defined(__STDC__)
    # define PREDEF_STANDARD_C_1989
    # if defined(__STDC_VERSION__)
    #  define PREDEF_STANDARD_C_1990
    #  if (__STDC_VERSION__ >= 199409L)
    #   define PREDEF_STANDARD_C_1994
    #  endif
    #  if (__STDC_VERSION__ >= 199901L)
    #   define PREDEF_STANDARD_C_1999
    #  endif
    # endif
    #endif

