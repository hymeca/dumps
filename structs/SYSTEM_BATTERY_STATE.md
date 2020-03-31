# SYSTEM_BATTERY_STATE

```C
typedef struct { // same size in both x86 and x64
   BOOLEAN AcOnLine;                                            // 0x000 0x000
   BOOLEAN BatteryPresent;                                      // 0x001 0x001
   BOOLEAN Charging;                                            // 0x002 0x002
   BOOLEAN Discharging;                                         // 0x003 0x003
   BYTE    Spare1[3];                                           // 0x004 0x004
   BYTE    Tag;                                                 // 0x007 0x007
   ULONG   MaxCapacity;                                         // 0x008 0x008
   ULONG   RemainingCapacity;                                   // 0x00c 0x00c
   ULONG   Rate;                                                // 0x010 0x010
   ULONG   EstimatedTime;                                       // 0x014 0x014
   ULONG   DefaultAlert1;                                       // 0x018 0x018
   ULONG   DefaultAlert2;                                       // 0x01c 0x01c
} SYSTEM_BATTERY_STATE, *PSYSTEM_BATTERY_STATE;
```
