# SYSTEM_LOGICAL_PROCESSOR_INFORMATION_EX

```C
typedef struct _SYSTEM_LOGICAL_PROCESSOR_INFORMATION_EX { // x86 = 76, x64 = 80
   LOGICAL_PROCESSOR_RELATIONSHIP Relationship;                            // 0x000 0x000
   ULONG                          Size;                                    // 0x004 0x004
   union {
      PROCESSOR_RELATIONSHIP      Processor;                               // 0x008 0x008
      NUMA_NODE_RELATIONSHIP      NumaNode;                                // 0x008 0x008
      CACHE_RELATIONSHIP          Cache;                                   // 0x008 0x008
      GROUP_RELATIONSHIP          Group;                                   // 0x008 0x008
   } DUMMYUNIONNAME;
} SYSTEM_LOGICAL_PROCESSOR_INFORMATION_EX, *PSYSTEM_LOGICAL_PROCESSOR_INFORMATION_EX;
```
