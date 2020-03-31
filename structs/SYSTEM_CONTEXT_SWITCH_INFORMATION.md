# SYSTEM_CONTEXT_SWITCH_INFORMATION

```C
typedef struct _SYSTEM_CONTEXT_SWITCH_INFORMATION { // same size in both x86 and x64
   ULONG ContextSwitches;                                                     // 0x000 0x000
   ULONG FindAny;                                                             // 0x004 0x004
   ULONG FindLast;                                                            // 0x008 0x008
   ULONG FindIdeal;                                                           // 0x00c 0x00c
   ULONG IdleAny;                                                             // 0x010 0x010
   ULONG IdleCurrent;                                                         // 0x014 0x014
   ULONG IdleLast;                                                            // 0x018 0x018
   ULONG IdleIdeal;                                                           // 0x01c 0x01c
   ULONG PreemptAny;                                                          // 0x020 0x020
   ULONG PreemptCurrent;                                                      // 0x024 0x024
   ULONG PreemptLast;                                                         // 0x028 0x028
   ULONG SwitchToIdle;                                                        // 0x02c 0x02c
} SYSTEM_CONTEXT_SWITCH_INFORMATION, *PSYSTEM_CONTEXT_SWITCH_INFORMATION;
```
