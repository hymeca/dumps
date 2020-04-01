# SYSTEM_NUMA_INFORMATION

```C
typedef struct _SYSTEM_NUMA_INFORMATION { // x86 = 264, x64 = 1032
   ULONG          HighestNodeNumber;                               // 0x000 0x000
   ULONG          Reserved;                                        // 0x004 0x004
   union {
      GROUP_AFFINITY ActiveProcessorsGroupAffinity[64];            // 0x008 0x008
      ULONGLONG      AvailableMemory[64];                          // 0x008 0x008
      ULONGLONG      Pad[128];                                     // 0x008 0x008
   } DUMMYUNIONNAME;
} SYSTEM_NUMA_INFORMATION, *PSYSTEM_NUMA_INFORMATION;
```
