# SYSTEM_CALL_TIME_INFORMATION

```C
typedef struct _SYSTEM_CALL_TIME_INFORMATION { // same size in both x86 and x64
   ULONG         Length;                                                    // 0x000 0x000
   ULONG         TotalCalls;                                                // 0x004 0x004
   LARGE_INTEGER TimeOfCalls[1];                                            // 0x008 0x008
} SYSTEM_CALL_TIME_INFORMATION, *PSYSTEM_CALL_TIME_INFORMATION;
```
