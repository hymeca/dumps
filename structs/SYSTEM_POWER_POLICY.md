# SYSTEM_POWER_POLICY

```C
typedef struct _SYSTEM_POWER_POLICY { // same size in both x86 and x64
   ULONG               Revision;                                   // 0x000 0x000
   POWER_ACTION_POLICY PowerButton;                                // 0x004 0x004
   POWER_ACTION_POLICY SleepButton;                                // 0x010 0x010
   POWER_ACTION_POLICY LidClose;                                   // 0x01c 0x01c
   SYSTEM_POWER_STATE  LidOpenWake;                                // 0x028 0x028
   ULONG               Reserved;                                   // 0x02c 0x02c
   POWER_ACTION_POLICY Idle;                                       // 0x030 0x030
   ULONG               IdleTimeout;                                // 0x03c 0x03c
   UCHAR               IdleSensitivity;                            // 0x040 0x040
   UCHAR               DynamicThrottle;                            // 0x041 0x041
   UCHAR               Spare2[2];                                  // 0x042 0x042
   SYSTEM_POWER_STATE  MinSleep;                                   // 0x044 0x044
   SYSTEM_POWER_STATE  MaxSleep;                                   // 0x048 0x048
   SYSTEM_POWER_STATE  ReducedLatencySleep;                        // 0x04c 0x04c
   ULONG               WinLogonFlags;                              // 0x050 0x050
   ULONG               Spare3;                                     // 0x054 0x054
   ULONG               DozeS4Timeout;                              // 0x058 0x058
   ULONG               BroadcastCapacityResolution;                // 0x05c 0x05c
   SYSTEM_POWER_LEVEL  DischargePolicy[4];                         // 0x060 0x060
   ULONG               VideoTimeout;                               // 0x0c0 0x0c0
   BOOLEAN             VideoDimDisplay;                            // 0x0c4 0x0c4
   ULONG               VideoReserved[3];                           // 0x0c8 0x0c8
   ULONG               SpindownTimeout;                            // 0x0d4 0x0d4
   BOOLEAN             OptimizeForPower;                           // 0x0d8 0x0d8
   UCHAR               FanThrottleTolerance;                       // 0x0d9 0x0d9
   UCHAR               ForcedThrottle;                             // 0x0da 0x0da
   UCHAR               MinThrottle;                                // 0x0db 0x0db
   POWER_ACTION_POLICY OverThrottled;                              // 0x0dc 0x0dc
} SYSTEM_POWER_POLICY, *PSYSTEM_POWER_POLICY;
```
