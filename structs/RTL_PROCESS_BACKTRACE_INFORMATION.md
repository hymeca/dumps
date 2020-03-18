# RTL_PROCESS_BACKTRACE_INFORMATION

```C
typedef struct _RTL_PROCESS_BACKTRACE_INFORMATION { // x86 = 140, x64 = 272
   PSTR   SymbolicBackTrace;                              // 0x000 0x000
   ULONG  TraceCount;                                     // 0x004 0x008
   USHORT Index;                                          // 0x008 0x00c
   USHORT Depth;                                          // 0x00a 0x00e
   PVOID  BackTrace[32];                                  // 0x00c 0x010
} RTL_PROCESS_BACKTRACE_INFORMATION, *PRTL_PROCESS_BACKTRACE_INFORMATION;
```
