# PROCESS_WS_WATCH_INFORMATION_EX

```C
typedef struct _PROCESS_WS_WATCH_INFORMATION_EX { // x86 = 16, x64 = 32
   PROCESS_WS_WATCH_INFORMATION BasicInfo;                                    // 0x000 0x000
   ULONG_PTR FaultingThreadId;                                                // 0x008 0x010
   ULONG_PTR Flags;                                                           // 0x00c 0x018
} PROCESS_WS_WATCH_INFORMATION_EX, *PPROCESS_WS_WATCH_INFORMATION_EX;
```
