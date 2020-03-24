# RTL_DEBUG_INFORMATION32

```C
typedef struct _RTL_DEBUG_INFORMATION32 { // same size in both x86 and x64
   ULONG SectionHandleClient;                            // 0x000 0x000
   ULONG ViewBaseClient;                                 // 0x004 0x004
   ULONG ViewBaseTarget;                                 // 0x008 0x008
   ULONG ViewBaseDelta;                                  // 0x00c 0x00c
   ULONG EventPairClient;                                // 0x010 0x010
   ULONG EventPairTarget;                                // 0x014 0x014
   ULONG TargetProcessId;                                // 0x018 0x018
   ULONG TargetThreadHandle;                             // 0x01c 0x01c
   ULONG Flags;                                          // 0x020 0x020
   ULONG OffsetFree;                                     // 0x024 0x024
   ULONG CommitSize;                                     // 0x028 0x028
   ULONG ViewSize;                                       // 0x02c 0x02c
   ULONG Modules;                                        // 0x030 0x030
   ULONG ModulesEx;                                      // 0x030 0x030
   ULONG BackTraces;                                     // 0x034 0x034
   ULONG Heaps;                                          // 0x038 0x038
   ULONG Locks;                                          // 0x03c 0x03c
   ULONG SpecificHeap;                                   // 0x040 0x040
   ULONG TargetProcessHandle;                            // 0x044 0x044
   ULONG VerifierOptions;                                // 0x048 0x048
   ULONG ProcessHeap;                                    // 0x04c 0x04c
   ULONG CriticalSectionHandle;                          // 0x050 0x050
   ULONG CriticalSectionOwnerThread;                     // 0x054 0x054
   ULONG Reserved[4];                                    // 0x058 0x058
} RTL_DEBUG_INFORMATION32, *PRTL_DEBUG_INFORMATION32;
```
