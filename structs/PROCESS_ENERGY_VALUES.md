# PROCESS_ENERGY_VALUES

```C
typedef struct _PROCESS_ENERGY_VALUES { // same size in both x86 and x64
   ULONGLONG                   Cycles[4][2];                                   // 0x000 0x000
   ULONGLONG                   DiskEnergy;                                     // 0x040 0x040
   ULONGLONG                   NetworkTailEnergy;                              // 0x048 0x048
   ULONGLONG                   MBBTailEnergy;                                  // 0x050 0x050
   ULONGLONG                   NetworkTxRxBytes;                               // 0x058 0x058
   ULONGLONG                   MBBTxRxBytes;                                   // 0x060 0x060
   union {
      ENERGY_STATE_DURATION    Durations[3];                                   // 0x068 0x068
      struct {
         ENERGY_STATE_DURATION ForegroundDuration;                             // 0x068 0x068
         ENERGY_STATE_DURATION DesktopVisibleDuration;                         // 0x070 0x070
         ENERGY_STATE_DURATION PSMForegroundDuration;                          // 0x078 0x078
      };
   };
   ULONG                       CompositionRendered;                            // 0x080 0x080
   ULONG                       CompositionDirtyGenerated;                      // 0x084 0x084
   ULONG                       CompositionDirtyPropagated;                     // 0x088 0x088
   ULONG                       Reserved1;                                      // 0x08c 0x08c
   ULONGLONG                   AttributedCycles[4][2];                         // 0x090 0x090
   ULONGLONG                   WorkOnBehalfCycles[4][2];                       // 0x0d0 0x0d0
} PROCESS_ENERGY_VALUES, *PPROCESS_ENERGY_VALUES;
```
