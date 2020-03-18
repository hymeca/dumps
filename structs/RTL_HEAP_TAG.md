# RTL_HEAP_TAG

```C
typedef struct _RTL_HEAP_TAG { // x86 = 64, x64 = 72
   ULONG  NumberOfAllocations;                            // 0x000 0x000
   ULONG  NumberOfFrees;                                  // 0x004 0x004
   SIZE_T BytesAllocated;                                 // 0x008 0x008
   USHORT TagIndex;                                       // 0x00c 0x010
   USHORT CreatorBackTraceIndex;                          // 0x00e 0x012
   WCHAR  TagName[24];                                    // 0x010 0x014
} RTL_HEAP_TAG, *PRTL_HEAP_TAG;
```
