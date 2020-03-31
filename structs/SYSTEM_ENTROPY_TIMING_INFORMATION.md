# SYSTEM_ENTROPY_TIMING_INFORMATION

```C
typedef struct _SYSTEM_ENTROPY_TIMING_INFORMATION { // x86 = 12, x64 = 24
   PVOID EntropyRoutine;                                                      // 0x000 0x000
   PVOID InitializationRoutine;                                               // 0x004 0x008
   PVOID InitializationContext;                                               // 0x008 0x010
} SYSTEM_ENTROPY_TIMING_INFORMATION, *PSYSTEM_ENTROPY_TIMING_INFORMATION;
```
