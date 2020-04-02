# SYSTEM_PROCESSOR_POWER_INFORMATION

```C
typedef struct _SYSTEM_PROCESSOR_POWER_INFORMATION { // same size in both x86 and x64
   UCHAR     CurrentFrequency;                                              // 0x000 0x000
   UCHAR     ThermalLimitFrequency;                                         // 0x001 0x001
   UCHAR     ConstantThrottleFrequency;                                     // 0x002 0x002
   UCHAR     DegradedThrottleFrequency;                                     // 0x003 0x003
   UCHAR     LastBusyFrequency;                                             // 0x004 0x004
   UCHAR     LastC3Frequency;                                               // 0x005 0x005
   UCHAR     LastAdjustedBusyFrequency;                                     // 0x006 0x006
   UCHAR     ProcessorMinThrottle;                                          // 0x007 0x007
   UCHAR     ProcessorMaxThrottle;                                          // 0x008 0x008
   ULONG     NumberOfFrequencies;                                           // 0x00c 0x00c
   ULONG     PromotionCount;                                                // 0x010 0x010
   ULONG     DemotionCount;                                                 // 0x014 0x014
   ULONG     ErrorCount;                                                    // 0x018 0x018
   ULONG     RetryCount;                                                    // 0x01c 0x01c
   ULONGLONG CurrentFrequencyTime;                                          // 0x020 0x020
   ULONGLONG CurrentProcessorTime;                                          // 0x028 0x028
   ULONGLONG CurrentProcessorIdleTime;                                      // 0x030 0x030
   ULONGLONG LastProcessorTime;                                             // 0x038 0x038
   ULONGLONG LastProcessorIdleTime;                                         // 0x040 0x040
   ULONGLONG Energy;                                                        // 0x048 0x048
} SYSTEM_PROCESSOR_POWER_INFORMATION, *PSYSTEM_PROCESSOR_POWER_INFORMATION;
```
