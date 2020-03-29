# PROCESS_HEAP_INFORMATION

```C
typedef struct _PROCESS_HEAP_INFORMATION { // x86 = 16, x64 = 32
   SIZE_T    ReserveSize;                                   // 0x000 0x000
   SIZE_T    CommitSize;                                    // 0x004 0x008
   ULONG     NumberOfHeaps;                                 // 0x008 0x010
   ULONG_PTR FirstHeapInformationOffset;                    // 0x00c 0x018
} PROCESS_HEAP_INFORMATION, *PPROCESS_HEAP_INFORMATION;
```
