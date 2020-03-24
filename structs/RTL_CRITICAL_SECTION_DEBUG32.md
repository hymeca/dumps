# RTL_CRITICAL_SECTION_DEBUG32

```C
typedef struct _RTL_CRITICAL_SECTION_DEBUG32 { // same size in both x86 and x64
   USHORT       Type;                                           // 0x000 0x000
   USHORT       CreatorBackTraceIndex;                          // 0x002 0x002
   ULONG        CriticalSection;                                // 0x004 0x004
   LIST_ENTRY32 ProcessLocksList;                               // 0x008 0x008
   ULONG        EntryCount;                                     // 0x010 0x010
   ULONG        ContentionCount;                                // 0x014 0x014
   ULONG        Spare[2];                                       // 0x018 0x018
} RTL_CRITICAL_SECTION_DEBUG32, *PRTL_CRITICAL_SECTION_DEBUG32;
```
