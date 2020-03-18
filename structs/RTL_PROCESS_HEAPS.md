# RTL_PROCESS_HEAPS

```C
typedef struct _RTL_PROCESS_HEAPS { // x86 = 68, x64 = 96
   ULONG                NumberOfHeaps;                                  // 0x000 0x000
   RTL_HEAP_INFORMATION Heaps[1];                                       // 0x004 0x008
} RTL_PROCESS_HEAPS, *PRTL_PROCESS_HEAPS;
```
