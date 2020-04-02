# SYSTEM_PROCESSOR_PERFORMANCE_HITCOUNT

```C
typedef struct _SYSTEM_PROCESSOR_PERFORMANCE_HITCOUNT { // same size in both x86 and x64
   ULONGLONG Hits;                                                            // 0x000 0x000
   BYTE      PercentFrequency;                                                // 0x008 0x008
} SYSTEM_PROCESSOR_PERFORMANCE_HITCOUNT, *PSYSTEM_PROCESSOR_PERFORMANCE_HITCOUNT;
```
