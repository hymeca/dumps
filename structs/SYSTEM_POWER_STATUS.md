# SYSTEM_POWER_STATUS

```C
typedef struct _SYSTEM_POWER_STATUS { // same size in both x86 and x64
   BYTE  ACLineStatus;                                             // 0x000 0x000
   BYTE  BatteryFlag;                                              // 0x001 0x001
   BYTE  BatteryLifePercent;                                       // 0x002 0x002
   BYTE  SystemStatusFlag;                                         // 0x003 0x003
   ULONG BatteryLifeTime;                                          // 0x004 0x004
   ULONG BatteryFullLifeTime;                                      // 0x008 0x008
} SYSTEM_POWER_STATUS, *LPSYSTEM_POWER_STATUS;
```
