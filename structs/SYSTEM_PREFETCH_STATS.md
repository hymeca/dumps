# SYSTEM_PREFETCH_STATS

```C
typedef struct _SYSTEM_PREFETCH_STATS { // same size in both x86 and x64
   ULONG DemandFilePageCount;                                                 // 0x000 0x000
   ULONG DemandFileIOCount;                                                   // 0x004 0x004
   ULONG TrickleFilePageCount;                                                // 0x008 0x008
   ULONG TrickleFileIOCount;                                                  // 0x00c 0x00c
   ULONG DemandPrivatePageCount;                                              // 0x010 0x010
   ULONG DemandPrivateIOCount;                                                // 0x014 0x014
   ULONG TricklePrivatePageCount;                                             // 0x018 0x018
   ULONG TricklePrivateIOCount;                                               // 0x01c 0x01c
} SYSTEM_PREFETCH_STATS, *PSYSTEM_PREFETCH_STATS;
```
