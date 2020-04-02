# SYSTEM_PROCESSOR_PERFORMANCE_STATE_DISTRIBUTION

```C
typedef struct _SYSTEM_PROCESSOR_PERFORMANCE_STATE_DISTRIBUTION { // same size in both x86 and x64
   ULONG                                 ProcessorNumber;                     // 0x000 0x000
   ULONG                                 StateCount;                          // 0x004 0x004
   SYSTEM_PROCESSOR_PERFORMANCE_HITCOUNT States[1];                           // 0x008 0x008
} SYSTEM_PROCESSOR_PERFORMANCE_STATE_DISTRIBUTION,
*PSYSTEM_PROCESSOR_PERFORMANCE_STATE_DISTRIBUTION;
```
