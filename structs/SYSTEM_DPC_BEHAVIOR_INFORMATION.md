# SYSTEM_DPC_BEHAVIOR_INFORMATION

```C
typedef struct _SYSTEM_DPC_BEHAVIOR_INFORMATION { // same size in both x86 and x64
   ULONG Spare;                                                               // 0x000 0x000
   ULONG DpcQueueDepth;                                                       // 0x004 0x004
   ULONG MinimumDpcRate;                                                      // 0x008 0x008
   ULONG AdjustDpcThreshold;                                                  // 0x00c 0x00c
   ULONG IdealDpcRate;                                                        // 0x010 0x010
} SYSTEM_DPC_BEHAVIOR_INFORMATION, *PSYSTEM_DPC_BEHAVIOR_INFORMATION;
```
