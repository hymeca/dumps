# PROCESS_UPTIME_INFORMATION

```C
typedef struct _PROCESS_UPTIME_INFORMATION { // same size in both x86 and x64
   ULONGLONG QueryInterruptTime;                                          // 0x000 0x000
   ULONGLONG QueryUnbiasedTime;                                           // 0x008 0x008
   ULONGLONG EndInterruptTime;                                            // 0x010 0x010
   ULONGLONG TimeSinceCreation;                                           // 0x018 0x018
   ULONGLONG Uptime;                                                      // 0x020 0x020
   ULONGLONG SuspendedTime;                                               // 0x028 0x028
   union {
      ULONG HangCount : 4;                                                // 0x030 0x030
      ULONG GhostCount : 4;                                               // 0x030 0x030
      ULONG Crashed : 1;                                                  // 0x030 0x030
      ULONG Terminated : 1;                                               // 0x030 0x030
   };
} PROCESS_UPTIME_INFORMATION, *PPROCESS_UPTIME_INFORMATION;
```
