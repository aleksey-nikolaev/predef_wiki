
 ## Data Models ##

Data type | LP32 | ILP32 | ILP64 | LLP64 | LP64
---|---|---|---|---|---
char | 8 | 8 | 8 | 8 | 8
short | 16 | 16 | 16 | 16 | 16
int | 16 | 32 | 64 | 32 | 32
long | 32 | 32 | 64 | 32 | 64
long long | | | | 64 |
pointer | 32 |    32  |    64  |    64  |   64

## ILP32 ##

Macro | Description
---|---
`_ILP32` | Defined by HP aCC and Sun Studio
`__ILP32__` | Defined by GNU C

## LP64 ##

Macro | Description
---|---
`_LP64` | Defined by HP aCC and Sun Studio
`__LP64__` | Defined by GNU C

