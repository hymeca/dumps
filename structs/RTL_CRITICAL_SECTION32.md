# RTL_CRITICAL_SECTION32

```C
typedef struct _RTL_CRITICAL_SECTION32 { // same size in both x86 and x64
   ULONG DebugInfo;                                      // 0x000 0x000
   LONG  LockCount;                                      // 0x004 0x004
   LONG  RecursionCount;                                 // 0x008 0x008
   ULONG OwningThread;                                   // 0x00c 0x00c
   ULONG LockSemaphore;                                  // 0x010 0x010
   ULONG SpinCount;                                      // 0x014 0x014
} RTL_CRITICAL_SECTION32, *PRTL_CRITICAL_SECTION32;
```
