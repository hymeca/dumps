# RTL_CRITICAL_SECTION64

```C
typedef struct _RTL_CRITICAL_SECTION64 { // same size in both x86 and x64
   ULONGLONG DebugInfo;                                      // 0x000 0x000
   LONG      LockCount;                                      // 0x008 0x008
   LONG      RecursionCount;                                 // 0x00c 0x00c
   ULONGLONG OwningThread;                                   // 0x010 0x010
   ULONGLONG LockSemaphore;                                  // 0x018 0x018
   ULONGLONG SpinCount;                                      // 0x020 0x020
} RTL_CRITICAL_SECTION64, *PRTL_CRITICAL_SECTION64;
```
