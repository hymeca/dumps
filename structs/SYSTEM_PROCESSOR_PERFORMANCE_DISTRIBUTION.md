# SYSTEM_PROCESSOR_PERFORMANCE_DISTRIBUTION

```C
typedef struct _SYSTEM_PROCESSOR_PERFORMANCE_DISTRIBUTION { // same size in both x86 and x64
   ULONG ProcessorCount;                                                      // 0x000 0x000
   ULONG Offsets[1];                                                          // 0x004 0x004
} SYSTEM_PROCESSOR_PERFORMANCE_DISTRIBUTION, *PSYSTEM_PROCESSOR_PERFORMANCE_DISTRIBUTION;
```
