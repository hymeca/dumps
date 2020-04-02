# SYSTEM_PROCESSOR_IDLE_INFORMATION

```C
typedef struct _SYSTEM_PROCESSOR_IDLE_INFORMATION { // same size in both x86 and x64
   ULONGLONG IdleTime;                                                        // 0x000 0x000
   ULONGLONG C1Time;                                                          // 0x008 0x008
   ULONGLONG C2Time;                                                          // 0x010 0x010
   ULONGLONG C3Time;                                                          // 0x018 0x018
   ULONG     C1Transitions;                                                   // 0x020 0x020
   ULONG     C2Transitions;                                                   // 0x024 0x024
   ULONG     C3Transitions;                                                   // 0x028 0x028
   ULONG     Padding;                                                         // 0x02c 0x02c
} SYSTEM_PROCESSOR_IDLE_INFORMATION, *PSYSTEM_PROCESSOR_IDLE_INFORMATION;
```
