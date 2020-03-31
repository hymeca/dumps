# SYSTEM_FILECACHE_INFORMATION

```C
typedef struct _SYSTEM_FILECACHE_INFORMATION { // x86 = 36, x64 = 64
   SIZE_T CurrentSize;                                          // 0x000 0x000
   SIZE_T PeakSize;                                             // 0x004 0x008
   ULONG  PageFaultCount;                                       // 0x008 0x010
   SIZE_T MinimumWorkingSet;                                    // 0x00c 0x018
   SIZE_T MaximumWorkingSet;                                    // 0x010 0x020
   SIZE_T CurrentSizeIncludingTransitionInPages;                // 0x014 0x028
   SIZE_T PeakSizeIncludingTransitionInPages;                   // 0x018 0x030
   ULONG  TransitionRePurposeCount;                             // 0x01c 0x038
   ULONG  Flags;                                                // 0x020 0x03c
} SYSTEM_FILECACHE_INFORMATION, *PSYSTEM_FILECACHE_INFORMATION;
```
