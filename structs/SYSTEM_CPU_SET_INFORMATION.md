# SYSTEM_CPU_SET_INFORMATION

```C
typedef struct _SYSTEM_CPU_SET_INFORMATION { // same size in both x86 and x64
   ULONG                    Size;                                   // 0x000 0x000
   CPU_SET_INFORMATION_TYPE Type;                                   // 0x004 0x004
   union {                                                          // 0x008 0x008
      struct {
         ULONG              Id;                                     // 0x000 0x000
         USHORT             Group;                                  // 0x004 0x004
         UCHAR              LogicalProcessorIndex;                  // 0x006 0x006
         UCHAR              CoreIndex;                              // 0x007 0x007
         UCHAR              LastLevelCacheIndex;                    // 0x008 0x008
         UCHAR              NumaNodeIndex;                          // 0x009 0x009
         UCHAR              EfficiencyClass;                        // 0x00a 0x00a
         union {
            UCHAR           AllFlags;                               // 0x00b 0x00b
            struct {
               UCHAR        Parked : 1;                             // 0x00b 0x00b
               UCHAR        Allocated : 1;                          // 0x00b 0x00b
               UCHAR        AllocatedToTargetProcess : 1;           // 0x00b 0x00b
               UCHAR        RealTime : 1;                           // 0x00b 0x00b
               UCHAR        ReservedFlags : 4;                      // 0x00b 0x00b
            } DUMMYSTRUCTNAME;
         } DUMMYUNIONNAME2;
         union {
            ULONG           Reserved;                               // 0x00c 0x00c
            UCHAR           SchedulingClass;                        // 0x00c 0x00c
         } DUMMYUNIONNAME3;
         ULONGLONG          AllocationTag;                          // 0x010 0x010
      } CpuSet;
   } DUMMYUNIONNAME1;
} SYSTEM_CPU_SET_INFORMATION, *PSYSTEM_CPU_SET_INFORMATION;
```
