# SYSTEM_MEMORY_USAGE_INFORMATION

```C
typedef struct _SYSTEM_MEMORY_USAGE_INFORMATION { // same size in both x86 and x64
   ULONGLONG TotalPhysicalBytes;                                              // 0x000 0x000
   ULONGLONG AvailableBytes;                                                  // 0x008 0x008
   LONGLONG  ResidentAvailableBytes;                                          // 0x010 0x010
   ULONGLONG CommittedBytes;                                                  // 0x018 0x018
   ULONGLONG SharedCommittedBytes;                                            // 0x020 0x020
   ULONGLONG CommitLimitBytes;                                                // 0x028 0x028
   ULONGLONG PeakCommitmentBytes;                                             // 0x030 0x030
} SYSTEM_MEMORY_USAGE_INFORMATION, *PSYSTEM_MEMORY_USAGE_INFORMATION;
```
