# SYSTEM_VERIFIER_INFORMATION

```C
typedef struct _SYSTEM_VERIFIER_INFORMATION { // x86 = 120, x64 = 144
   ULONG          NextEntryOffset;                              // 0x000 0x000
   ULONG          Level;                                        // 0x004 0x004
   ULONG          RuleClasses[2];                               // 0x008 0x008
   ULONG          TriageContext;                                // 0x010 0x010
   ULONG          AreAllDriversBeingVerified;                   // 0x014 0x014
   UNICODE_STRING DriverName;                                   // 0x018 0x018
   ULONG          RaiseIrqls;                                   // 0x020 0x028
   ULONG          AcquireSpinLocks;                             // 0x024 0x02c
   ULONG          SynchronizeExecutions;                        // 0x028 0x030
   ULONG          AllocationsAttempted;                         // 0x02c 0x034
   ULONG          AllocationsSucceeded;                         // 0x030 0x038
   ULONG          AllocationsSucceededSpecialPool;              // 0x034 0x03c
   ULONG          AllocationsWithNoTag;                         // 0x038 0x040
   ULONG          TrimRequests;                                 // 0x03c 0x044
   ULONG          Trims;                                        // 0x040 0x048
   ULONG          AllocationsFailed;                            // 0x044 0x04c
   ULONG          AllocationsFailedDeliberately;                // 0x048 0x050
   ULONG          Loads;                                        // 0x04c 0x054
   ULONG          Unloads;                                      // 0x050 0x058
   ULONG          UnTrackedPool;                                // 0x054 0x05c
   ULONG          CurrentPagedPoolAllocations;                  // 0x058 0x060
   ULONG          CurrentNonPagedPoolAllocations;               // 0x05c 0x064
   ULONG          PeakPagedPoolAllocations;                     // 0x060 0x068
   ULONG          PeakNonPagedPoolAllocations;                  // 0x064 0x06c
   SIZE_T         PagedPoolUsageInBytes;                        // 0x068 0x070
   SIZE_T         NonPagedPoolUsageInBytes;                     // 0x06c 0x078
   SIZE_T         PeakPagedPoolUsageInBytes;                    // 0x070 0x080
   SIZE_T         PeakNonPagedPoolUsageInBytes;                 // 0x074 0x088
} SYSTEM_VERIFIER_INFORMATION, *PSYSTEM_VERIFIER_INFORMATION;
```
