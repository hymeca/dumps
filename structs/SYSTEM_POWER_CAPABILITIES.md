# SYSTEM_POWER_CAPABILITIES

```C
typedef struct { // same size in both x86 and x64
   BOOLEAN                 PowerButtonPresent;                            // 0x000 0x000
   BOOLEAN                 SleepButtonPresent;                            // 0x001 0x001
   BOOLEAN                 LidPresent;                                    // 0x002 0x002
   BOOLEAN                 SystemS1;                                      // 0x003 0x003
   BOOLEAN                 SystemS2;                                      // 0x004 0x004
   BOOLEAN                 SystemS3;                                      // 0x005 0x005
   BOOLEAN                 SystemS4;                                      // 0x006 0x006
   BOOLEAN                 SystemS5;                                      // 0x007 0x007
   BOOLEAN                 HiberFilePresent;                              // 0x008 0x008
   BOOLEAN                 FullWake;                                      // 0x009 0x009
   BOOLEAN                 VideoDimPresent;                               // 0x00a 0x00a
   BOOLEAN                 ApmPresent;                                    // 0x00b 0x00b
   BOOLEAN                 UpsPresent;                                    // 0x00c 0x00c
   BOOLEAN                 ThermalControl;                                // 0x00d 0x00d
   BOOLEAN                 ProcessorThrottle;                             // 0x00e 0x00e
   BYTE                    ProcessorMinThrottle;                          // 0x00f 0x00f
   BYTE                    ProcessorMaxThrottle;                          // 0x010 0x010
   BOOLEAN                 FastSystemS4;                                  // 0x011 0x011
   BOOLEAN                 Hiberboot;                                     // 0x012 0x012
   BOOLEAN                 WakeAlarmPresent;                              // 0x013 0x013
   BOOLEAN                 AoAc;                                          // 0x014 0x014
   BOOLEAN                 DiskSpinDown;                                  // 0x015 0x015
   BYTE                    HiberFileType;                                 // 0x016 0x016
   BOOLEAN                 AoAcConnectivitySupported;                     // 0x017 0x017
   BOOLEAN                 spare3[6];                                     // 0x018 0x018
   BOOLEAN                 SystemBatteriesPresent;                        // 0x01e 0x01e
   BOOLEAN                 BatteriesAreShortTerm;                         // 0x01f 0x01f
   BATTERY_REPORTING_SCALE BatteryScale[3];                               // 0x020 0x020
   SYSTEM_POWER_STATE      AcOnLineWake;                                  // 0x038 0x038
   SYSTEM_POWER_STATE      SoftLidWake;                                   // 0x03c 0x03c
   SYSTEM_POWER_STATE      RtcWake;                                       // 0x040 0x040
   SYSTEM_POWER_STATE      MinDeviceWakeState;                            // 0x044 0x044
   SYSTEM_POWER_STATE      DefaultLowLatencyWake;                         // 0x048 0x048
} SYSTEM_POWER_CAPABILITIES, *PSYSTEM_POWER_CAPABILITIES;
```
