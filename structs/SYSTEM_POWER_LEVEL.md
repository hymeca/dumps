# SYSTEM_POWER_LEVEL

```C
typedef struct { // same size in both x86 and x64
   BOOLEAN             Enable;                                        // 0x000 0x000
   BYTE                Spare[3];                                      // 0x001 0x001
   ULONG               BatteryLevel;                                  // 0x004 0x004
   POWER_ACTION_POLICY PowerPolicy;                                   // 0x008 0x008
   SYSTEM_POWER_STATE  MinSystemState;                                // 0x014 0x014
} SYSTEM_POWER_LEVEL, *PSYSTEM_POWER_LEVEL;
```
