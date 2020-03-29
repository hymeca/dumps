# PROCESS_HANDLE_INFORMATION

```C
typedef struct _PROCESS_HANDLE_INFORMATION { // same size in both x86 and x64
   ULONG HandleCount;                                                     // 0x000 0x000
   ULONG HandleCountHighWatermark;                                        // 0x004 0x004
} PROCESS_HANDLE_INFORMATION, *PPROCESS_HANDLE_INFORMATION;
```
