# PROCESS_WS_WATCH_INFORMATION

```C
typedef struct _PROCESS_WS_WATCH_INFORMATION { // x86 = 8, x64 = 16
   PVOID FaultingPc;                                                          // 0x000 0x000
   PVOID FaultingVa;                                                          // 0x004 0x008
} PROCESS_WS_WATCH_INFORMATION, *PPROCESS_WS_WATCH_INFORMATION;
```
