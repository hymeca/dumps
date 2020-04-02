# SYSTEM_SECURE_KERNEL_HYPERGUARD_PROFILE_INFORMATION

```C
typedef struct _SYSTEM_SECURE_KERNEL_HYPERGUARD_PROFILE_INFORMATION { // same size in both x86 and x64
   ULONG     ExtentCount;                                                     // 0x000 0x000
   ULONG     ValidStructureSize;                                              // 0x004 0x004
   ULONG     NextExtentIndex;                                                 // 0x008 0x008
   ULONG     ExtentRestart;                                                   // 0x00c 0x00c
   ULONG     CycleCount;                                                      // 0x010 0x010
   ULONG     TimeoutCount;                                                    // 0x014 0x014
   ULONGLONG CycleTime;                                                       // 0x018 0x018
   ULONGLONG CycleTimeMax;                                                    // 0x020 0x020
   ULONGLONG ExtentTime;                                                      // 0x028 0x028
   ULONG     ExtentTimeIndex;                                                 // 0x030 0x030
   ULONG     ExtentTimeMaxIndex;                                              // 0x034 0x034
   ULONGLONG ExtentTimeMax;                                                   // 0x038 0x038
   ULONGLONG HyperFlushTimeMax;                                               // 0x040 0x040
   ULONGLONG TranslateVaTimeMax;                                              // 0x048 0x048
   ULONGLONG DebugExemptionCount;                                             // 0x050 0x050
   ULONGLONG TbHitCount;                                                      // 0x058 0x058
   ULONGLONG TbMissCount;                                                     // 0x060 0x060
   ULONGLONG VinaPendingYield;                                                // 0x068 0x068
   ULONGLONG HashCycles;                                                      // 0x070 0x070
   ULONG     HistogramOffset;                                                 // 0x078 0x078
   ULONG     HistogramBuckets;                                                // 0x07c 0x07c
   ULONG     HistogramShift;                                                  // 0x080 0x080
   ULONG     Reserved1;                                                       // 0x084 0x084
   ULONGLONG PageNotPresentCount;                                             // 0x088 0x088
} SYSTEM_SECURE_KERNEL_HYPERGUARD_PROFILE_INFORMATION, *PSYSTEM_SECURE_KERNEL_HYPERGUARD_PROFILE_INFORMATION;
```
