# PROCESS_CYCLE_TIME_INFORMATION

```C
typedef struct _PROCESS_CYCLE_TIME_INFORMATION { // same size in both x86 and x64
   ULONGLONG AccumulatedCycles;                              // 0x000 0x000
   ULONGLONG CurrentCycleCount;                              // 0x008 0x008
} PROCESS_CYCLE_TIME_INFORMATION, *PPROCESS_CYCLE_TIME_INFORMATION;
```
