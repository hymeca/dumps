# SYSTEM_TIMEOFDAY_INFORMATION

```C
typedef struct _SYSTEM_TIMEOFDAY_INFORMATION { // same size in both x86 and x64
   LARGE_INTEGER BootTime;                                                 // 0x000 0x000
   LARGE_INTEGER CurrentTime;                                              // 0x008 0x008
   LARGE_INTEGER TimeZoneBias;                                             // 0x010 0x010
   ULONG         TimeZoneId;                                               // 0x018 0x018
   ULONG         Reserved;                                                 // 0x01c 0x01c
   ULONGLONG     BootTimeBias;                                             // 0x020 0x020
   ULONGLONG     SleepTimeBias;                                            // 0x028 0x028
} SYSTEM_TIMEOFDAY_INFORMATION, *PSYSTEM_TIMEOFDAY_INFORMATION;
```
