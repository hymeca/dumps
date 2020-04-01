# SYSTEM_LOGICAL_PROCESSOR_INFORMATION

```C
typedef struct _SYSTEM_LOGICAL_PROCESSOR_INFORMATION { // x86 = 24, x64 = 32
   ULONG_PTR                      ProcessorMask;                        // 0x000 0x000
   LOGICAL_PROCESSOR_RELATIONSHIP Relationship;                         // 0x004 0x008
   union {
      struct {                                                          // 0x008 0x010
          BYTE                    Flags;
      } ProcessorCore;
      struct {                                                          // 0x008 0x010
         ULONG                    NodeNumber;
      } NumaNode;
      CACHE_DESCRIPTOR            Cache;                                // 0x008 0x010
      ULONGLONG                   Reserved[2];                          // 0x008 0x010
   } DUMMYUNIONNAME;
} SYSTEM_LOGICAL_PROCESSOR_INFORMATION, *PSYSTEM_LOGICAL_PROCESSOR_INFORMATION;
```
