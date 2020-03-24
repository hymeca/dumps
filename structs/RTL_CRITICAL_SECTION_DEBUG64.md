# RTL_CRITICAL_SECTION_DEBUG64

```C
typedef struct _RTL_CRITICAL_SECTION_DEBUG64 { // same size in both x86 and x64
   USHORT       Type;                                           // 0x000 0x000
   USHORT       CreatorBackTraceIndex;                          // 0x002 0x002
   ULONGLONG    CriticalSection;                                // 0x008 0x008
   LIST_ENTRY64 ProcessLocksList;                               // 0x010 0x010
   ULONG        EntryCount;                                     // 0x020 0x020
   ULONG        ContentionCount;                                // 0x024 0x024
   ULONG        Spare[2];                                       // 0x028 0x028
} RTL_CRITICAL_SECTION_DEBUG64, *PRTL_CRITICAL_SECTION_DEBUG64;
```
