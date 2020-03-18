# RTL_HEAP_INFORMATION

```C
typedef struct _RTL_HEAP_INFORMATION { // x86 = 64, x64 = 88
   PVOID           BaseAddress;                                    // 0x000 0x000
   ULONG           Flags;                                          // 0x004 0x008
   USHORT          EntryOverhead;                                  // 0x008 0x00c
   USHORT          CreatorBackTraceIndex;                          // 0x00a 0x00e
   SIZE_T          BytesAllocated;                                 // 0x00c 0x010
   SIZE_T          BytesCommitted;                                 // 0x010 0x018
   ULONG           NumberOfTags;                                   // 0x014 0x020
   ULONG           NumberOfEntries;                                // 0x018 0x024
   ULONG           NumberOfPseudoTags;                             // 0x01c 0x028
   ULONG           PseudoTagGranularity;                           // 0x020 0x02c
   ULONG           Reserved[5];                                    // 0x024 0x030
   PRTL_HEAP_TAG   Tags;                                           // 0x038 0x048
   PRTL_HEAP_ENTRY Entries;                                        // 0x03c 0x050
} RTL_HEAP_INFORMATION, *PRTL_HEAP_INFORMATION;
```
