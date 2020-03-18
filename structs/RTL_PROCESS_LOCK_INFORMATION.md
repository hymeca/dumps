# RTL_PROCESS_LOCK_INFORMATION

```C
typedef struct _RTL_PROCESS_LOCK_INFORMATION { // x86 = 36, x64 = 48
   PVOID  Address;                                        // 0x000 0x000
   USHORT Type;                                           // 0x004 0x008
   USHORT CreatorBackTraceIndex;                          // 0x006 0x00a
   PVOID  OwningThread;                                   // 0x008 0x010
   LONG   LockCount;                                      // 0x00c 0x018
   ULONG  ContentionCount;                                // 0x010 0x01c
   ULONG  EntryCount;                                     // 0x014 0x020
   LONG   RecursionCount;                                 // 0x018 0x024
   ULONG  NumberOfWaitingShared;                          // 0x01c 0x028
   ULONG  NumberOfWaitingExclusive;                       // 0x020 0x02c
} RTL_PROCESS_LOCK_INFORMATION, *PRTL_PROCESS_LOCK_INFORMATION;
```
