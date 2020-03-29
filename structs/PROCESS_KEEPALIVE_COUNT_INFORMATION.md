# PROCESS_KEEPALIVE_COUNT_INFORMATION

```C
typedef struct _PROCESS_KEEPALIVE_COUNT_INFORMATION { // same size in both x86 and x64
   ULONG WakeCount;                                                           // 0x000 0x000
   ULONG NoWakeCount;                                                         // 0x004 0x004
} PROCESS_KEEPALIVE_COUNT_INFORMATION, *PPROCESS_KEEPALIVE_COUNT_INFORMATION;
```
