# SYSTEM_PROCESS_INFORMATION

```C
typedef struct _SYSTEM_PROCESS_INFORMATION { // x86 = 184, x64 = 256
   ULONG          NextEntryOffset;                             // 0x000 0x000
   ULONG          NumberOfThreads;                             // 0x004 0x004
   LARGE_INTEGER  WorkingSetPrivateSize;                       // 0x008 0x008
   ULONG          HardFaultCount;                              // 0x010 0x010
   ULONG          NumberOfThreadsHighWatermark;                // 0x014 0x014
   ULONGLONG      CycleTime;                                   // 0x018 0x018
   LARGE_INTEGER  CreateTime;                                  // 0x020 0x020
   LARGE_INTEGER  UserTime;                                    // 0x028 0x028
   LARGE_INTEGER  KernelTime;                                  // 0x030 0x030
   UNICODE_STRING ImageName;                                   // 0x038 0x038
   KPRIORITY      BasePriority;                                // 0x040 0x048
   HANDLE         UniqueProcessId;                             // 0x044 0x050
   HANDLE         InheritedFromUniqueProcessId;                // 0x048 0x058
   ULONG          HandleCount;                                 // 0x04c 0x060
   ULONG          SessionId;                                   // 0x050 0x064
   ULONG_PTR      UniqueProcessKey;                            // 0x054 0x068
   SIZE_T         PeakVirtualSize;                             // 0x058 0x070
   SIZE_T         VirtualSize;                                 // 0x05c 0x078
   ULONG          PageFaultCount;                              // 0x060 0x080
   SIZE_T         PeakWorkingSetSize;                          // 0x064 0x088
   SIZE_T         WorkingSetSize;                              // 0x068 0x090
   SIZE_T         QuotaPeakPagedPoolUsage;                     // 0x06c 0x098
   SIZE_T         QuotaPagedPoolUsage;                         // 0x070 0x0a0
   SIZE_T         QuotaPeakNonPagedPoolUsage;                  // 0x074 0x0a8
   SIZE_T         QuotaNonPagedPoolUsage;                      // 0x078 0x0b0
   SIZE_T         PagefileUsage;                               // 0x07c 0x0b8
   SIZE_T         PeakPagefileUsage;                           // 0x080 0x0c0
   SIZE_T         PrivatePageCount;                            // 0x084 0x0c8
   LARGE_INTEGER  ReadOperationCount;                          // 0x088 0x0d0
   LARGE_INTEGER  WriteOperationCount;                         // 0x090 0x0d8
   LARGE_INTEGER  OtherOperationCount;                         // 0x098 0x0e0
   LARGE_INTEGER  ReadTransferCount;                           // 0x0a0 0x0e8
   LARGE_INTEGER  WriteTransferCount;                          // 0x0a8 0x0f0
   LARGE_INTEGER  OtherTransferCount;                          // 0x0b0 0x0f8
} SYSTEM_PROCESS_INFORMATION, *PSYSTEM_PROCESS_INFORMATION;
```
