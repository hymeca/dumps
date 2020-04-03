# SYSTEM_VERIFIER_COUNTERS_INFORMATION

```C
typedef struct _SYSTEM_VERIFIER_COUNTERS_INFORMATION { // x86 = 208, x64 = 272
   SYSTEM_VERIFIER_INFORMATION Legacy;                                   // 0x000 0x000
   ULONG  RaiseIrqls;                                                    // 0x078 0x090
   ULONG  AcquireSpinLocks;                                              // 0x07c 0x094
   ULONG  SynchronizeExecutions;                                         // 0x080 0x098
   ULONG  AllocationsWithNoTag;                                          // 0x084 0x09c
   ULONG  AllocationsFailed;                                             // 0x088 0x0a0
   ULONG  AllocationsFailedDeliberately;                                 // 0x08c 0x0a4
   SIZE_T LockedBytes;                                                   // 0x090 0x0a8
   SIZE_T PeakLockedBytes;                                               // 0x094 0x0b0
   SIZE_T MappedLockedBytes;                                             // 0x098 0x0b8
   SIZE_T PeakMappedLockedBytes;                                         // 0x09c 0x0c0
   SIZE_T MappedIoSpaceBytes;                                            // 0x0a0 0x0c8
   SIZE_T PeakMappedIoSpaceBytes;                                        // 0x0a4 0x0d0
   SIZE_T PagesForMdlBytes;                                              // 0x0a8 0x0d8
   SIZE_T PeakPagesForMdlBytes;                                          // 0x0ac 0x0e0
   SIZE_T ContiguousMemoryBytes;                                         // 0x0b0 0x0e8
   SIZE_T PeakContiguousMemoryBytes;                                     // 0x0b4 0x0f0
   ULONG  ExecutePoolTypes;                                              // 0x0b8 0x0f8
   ULONG  ExecutePageProtections;                                        // 0x0bc 0x0fc
   ULONG  ExecutePageMappings;                                           // 0x0c0 0x100
   ULONG  ExecuteWriteSections;                                          // 0x0c4 0x104
   ULONG  SectionAlignmentFailures;                                      // 0x0c8 0x108
   ULONG  IATInExecutableSection;                                        // 0x0cc 0x10c
} SYSTEM_VERIFIER_COUNTERS_INFORMATION, *PSYSTEM_VERIFIER_COUNTERS_INFORMATION;
```
