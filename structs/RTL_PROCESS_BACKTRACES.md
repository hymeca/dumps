# RTL_PROCESS_BACKTRACES

```C
typedef struct _RTL_PROCESS_BACKTRACES { // x86 = 156, x64 = 296
   ULONG_PTR                         CommittedMemory;                    // 0x000 0x000
   ULONG_PTR                         ReservedMemory;                     // 0x004 0x008
   ULONG                             NumberOfBackTraceLookups;           // 0x008 0x010
   ULONG                             NumberOfBackTraces;                 // 0x00c 0x014
   RTL_PROCESS_BACKTRACE_INFORMATION BackTraces[1];                      // 0x010 0x018
} RTL_PROCESS_BACKTRACES, *PRTL_PROCESS_BACKTRACES;
```
