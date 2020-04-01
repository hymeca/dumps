# SYSTEM_POOL_ENTRY

```C
typedef struct _SYSTEM_POOL_ENTRY { // x86 = 12, x64 = 16
   BOOLEAN  Allocated;                                               // 0x000 0x000
   BYTE     Spare0;                                                  // 0x001 0x001
   USHORT   AllocatorBackTraceIndex;                                 // 0x002 0x002
   ULONG    Size;                                                    // 0x004 0x004
   union {
      UCHAR Tag[4];                                                  // 0x008 0x008
      ULONG TagUlong;                                                // 0x008 0x008
      PVOID ProcessChargedQuota;                                     // 0x008 0x008
   } DUMMYUNIONNAME;
} SYSTEM_POOL_ENTRY, *PSYSTEM_POOL_ENTRY;
```
