# PROCESS_ENERGY_VALUES_EXTENSION

```C
typedef struct _PROCESS_ENERGY_VALUES_EXTENSION { // same size in both x86 and x64
   union {
      TIMELINE_BITMAP          Timelines[14];                                  // 0x000 0x000
      struct {
         TIMELINE_BITMAP       CpuTimeline;                                    // 0x000 0x000
         TIMELINE_BITMAP       DiskTimeline;                                   // 0x008 0x008
         TIMELINE_BITMAP       NetworkTimeline;                                // 0x010 0x010
         TIMELINE_BITMAP       MBBTimeline;                                    // 0x018 0x018
         TIMELINE_BITMAP       ForegroundTimeline;                             // 0x020 0x020
         TIMELINE_BITMAP       DesktopVisibleTimeline;                         // 0x028 0x028
         TIMELINE_BITMAP       CompositionRenderedTimeline;                    // 0x030 0x030
         TIMELINE_BITMAP       CompositionDirtyGeneratedTimeline;              // 0x038 0x038
         TIMELINE_BITMAP       CompositionDirtyPropagatedTimeline;             // 0x040 0x040
         TIMELINE_BITMAP       InputTimeline;                                  // 0x048 0x048
         TIMELINE_BITMAP       AudioInTimeline;                                // 0x050 0x050
         TIMELINE_BITMAP       AudioOutTimeline;                               // 0x058 0x058
         TIMELINE_BITMAP       DisplayRequiredTimeline;                        // 0x060 0x060
         TIMELINE_BITMAP       KeyboardInputTimeline;                          // 0x068 0x068
      };
   };
   union {
      ENERGY_STATE_DURATION    Durations[5];                                   // 0x070 0x070
      struct {
         ENERGY_STATE_DURATION InputDuration;                                  // 0x070 0x070
         ENERGY_STATE_DURATION AudioInDuration;                                // 0x078 0x078
         ENERGY_STATE_DURATION AudioOutDuration;                               // 0x080 0x080
         ENERGY_STATE_DURATION DisplayRequiredDuration;                        // 0x088 0x088
         ENERGY_STATE_DURATION PSMBackgroundDuration;                          // 0x090 0x090
      };
   };
   ULONG                       KeyboardInput;                                  // 0x098 0x098
   ULONG                       MouseInput;                                     // 0x09c 0x09c
} PROCESS_ENERGY_VALUES_EXTENSION, *PPROCESS_ENERGY_VALUES_EXTENSION;
```
