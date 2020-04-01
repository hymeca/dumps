# SYSTEM_POOLTAG

```C
typedef struct _SYSTEM_POOLTAG { // x86 = 28, x64 = 40
   union {
      UCHAR Tag[4];                                           // 0x000 0x000
      ULONG TagUlong;                                         // 0x000 0x000
   } DUMMYUNIONNAME;
   ULONG    PagedAllocs;                                      // 0x004 0x004
   ULONG    PagedFrees;                                       // 0x008 0x008
   SIZE_T   PagedUsed;                                        // 0x00c 0x010
   ULONG    NonPagedAllocs;                                   // 0x010 0x018
   ULONG    NonPagedFrees;                                    // 0x014 0x01c
   SIZE_T   NonPagedUsed;                                     // 0x018 0x020
} SYSTEM_POOLTAG, *PSYSTEM_POOLTAG;
```
