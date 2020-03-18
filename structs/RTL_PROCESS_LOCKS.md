# RTL_PROCESS_LOCKS

```C
typedef struct _RTL_PROCESS_LOCKS { // x86 = 40, x64 = 56
   ULONG                        NumberOfLocks;                             // 0x000 0x000
   RTL_PROCESS_LOCK_INFORMATION Locks[1];                                  // 0x004 0x008
} RTL_PROCESS_LOCKS, *PRTL_PROCESS_LOCKS;
```
