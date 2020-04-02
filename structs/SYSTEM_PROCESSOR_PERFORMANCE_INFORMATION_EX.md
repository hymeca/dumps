# SYSTEM_PROCESSOR_PERFORMANCE_INFORMATION_EX

```C
typedef struct _SYSTEM_PROCESSOR_PERFORMANCE_INFORMATION_EX { // same size in both x86 and x64
   LARGE_INTEGER IdleTime;                                                    // 0x000 0x000
   LARGE_INTEGER KernelTime;                                                  // 0x008 0x008
   LARGE_INTEGER UserTime;                                                    // 0x010 0x010
   LARGE_INTEGER DpcTime;                                                     // 0x018 0x018
   LARGE_INTEGER InterruptTime;                                               // 0x020 0x020
   ULONG         InterruptCount;                                              // 0x028 0x028
   ULONG         Spare0;                                                      // 0x02c 0x02c
   LARGE_INTEGER AvailableTime;                                               // 0x030 0x030
   LARGE_INTEGER Spare1;                                                      // 0x038 0x038
   LARGE_INTEGER Spare2;                                                      // 0x040 0x040
} SYSTEM_PROCESSOR_PERFORMANCE_INFORMATION_EX, *PSYSTEM_PROCESSOR_PERFORMANCE_INFORMATION_EX;
```
