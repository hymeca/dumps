# SYSTEM_POWER_INFORMATION

```C
typedef struct _SYSTEM_POWER_INFORMATION { // same size in both x86 and x64
   ULONG MaxIdlenessAllowed;                                            // 0x000 0x000
   ULONG Idleness;                                                      // 0x004 0x004
   ULONG TimeRemaining;                                                 // 0x008 0x008
   UCHAR CoolingMode;                                                   // 0x00c 0x00c
} SYSTEM_POWER_INFORMATION, *PSYSTEM_POWER_INFORMATION;
```
