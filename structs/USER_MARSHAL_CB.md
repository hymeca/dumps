# USER_MARSHAL_CB

```C
typedef struct _USER_MARSHAL_CB { // x86 = 28, x64 = 48
   ULONG                Flags;                                          // 0x000 0x000
   PMIDL_STUB_MESSAGE   pStubMsg;                                       // 0x004 0x008
   PFORMAT_STRING       pReserve;                                       // 0x008 0x010
   ULONG                Signature;                                      // 0x00c 0x018
   USER_MARSHAL_CB_TYPE CBType;                                         // 0x010 0x01c
   PFORMAT_STRING       pFormat;                                        // 0x014 0x020
   PFORMAT_STRING       pTypeFormat;                                    // 0x018 0x028
} USER_MARSHAL_CB, *PUSER_MARSHAL_CB;
```
