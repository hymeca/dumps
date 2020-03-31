# SYSTEM_ACCESS_FILTER_ACE

```C
typedef struct _SYSTEM_ACCESS_FILTER_ACE { // same size in both x86 and x64
   ACE_HEADER Header;                                                   // 0x000 0x000
   ULONG      Mask;                                                     // 0x004 0x004
   ULONG      SidStart;                                                 // 0x008 0x008
} SYSTEM_ACCESS_FILTER_ACE, *PSYSTEM_ACCESS_FILTER_ACE;
```
