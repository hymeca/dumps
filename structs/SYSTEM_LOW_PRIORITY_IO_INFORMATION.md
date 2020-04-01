# SYSTEM_LOW_PRIORITY_IO_INFORMATION

```C
typedef struct _SYSTEM_LOW_PRIORITY_IO_INFORMATION { // same size in both x86 and x64
   ULONG LowPriReadOperations;                                                // 0x000 0x000
   ULONG LowPriWriteOperations;                                               // 0x004 0x004
   ULONG KernelBumpedToNormalOperations;                                      // 0x008 0x008
   ULONG LowPriPagingReadOperations;                                          // 0x00c 0x00c
   ULONG KernelPagingReadsBumpedToNormal;                                     // 0x010 0x010
   ULONG LowPriPagingWriteOperations;                                         // 0x014 0x014
   ULONG KernelPagingWritesBumpedToNormal;                                    // 0x018 0x018
   ULONG BoostedIrpCount;                                                     // 0x01c 0x01c
   ULONG BoostedPagingIrpCount;                                               // 0x020 0x020
   ULONG BlanketBoostCount;                                                   // 0x024 0x024
} SYSTEM_LOW_PRIORITY_IO_INFORMATION, *PSYSTEM_LOW_PRIORITY_IO_INFORMATION;
```
