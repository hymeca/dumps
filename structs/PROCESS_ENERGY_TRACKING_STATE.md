# PROCESS_ENERGY_TRACKING_STATE

```C
typedef struct _PROCESS_ENERGY_TRACKING_STATE { // same size in both x86 and x64
   ULONG StateUpdateMask;                                // 0x000 0x000
   ULONG StateDesiredValue;                              // 0x004 0x004
   ULONG StateSequence;                                  // 0x008 0x008
   ULONG UpdateTag : 1;                                  // 0x00c 0x00c
   WCHAR Tag[64];                                        // 0x010 0x010
} PROCESS_ENERGY_TRACKING_STATE, *PPROCESS_ENERGY_TRACKING_STATE;
```
