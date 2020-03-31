# SYSTEM_BASIC_INFORMATION

```C
typedef struct _SYSTEM_BASIC_INFORMATION { // x86 = 44, x64 = 64
   ULONG     Reserved;                                      // 0x000 0x000
   ULONG     TimerResolution;                               // 0x004 0x004
   ULONG     PageSize;                                      // 0x008 0x008
   ULONG     NumberOfPhysicalPages;                         // 0x00c 0x00c
   ULONG     LowestPhysicalPageNumber;                      // 0x010 0x010
   ULONG     HighestPhysicalPageNumber;                     // 0x014 0x014
   ULONG     AllocationGranularity;                         // 0x018 0x018
   ULONG_PTR MinimumUserModeAddress;                        // 0x01c 0x020
   ULONG_PTR MaximumUserModeAddress;                        // 0x020 0x028
   ULONG_PTR ActiveProcessorsAffinityMask;                  // 0x024 0x030
   CCHAR     NumberOfProcessors;                            // 0x028 0x038
} SYSTEM_BASIC_INFORMATION, *PSYSTEM_BASIC_INFORMATION;
```
