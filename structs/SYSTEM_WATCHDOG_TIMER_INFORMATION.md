# SYSTEM_WATCHDOG_TIMER_INFORMATION

```C
typedef struct _SYSTEM_WATCHDOG_TIMER_INFORMATION { // same size in both x86 and x64
   WATCHDOG_INFORMATION_CLASS WdInfoClass;                                    // 0x000 0x000
   ULONG                      DataValue;                                      // 0x004 0x004
} SYSTEM_WATCHDOG_TIMER_INFORMATION, *PSYSTEM_WATCHDOG_TIMER_INFORMATION;
```
