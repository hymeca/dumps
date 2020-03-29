# PROCESS_TLS_INFORMATION

```C
typedef struct _PROCESS_TLS_INFORMATION { // x86 = 28, x64 = 40
   ULONG Flags;                                                               // 0x000 0x000
   ULONG OperationType;                                                       // 0x004 0x004
   ULONG ThreadDataCount;                                                     // 0x008 0x008
   ULONG TlsIndex;                                                            // 0x00c 0x00c
   ULONG PreviousCount;                                                       // 0x00c 0x00c
   THREAD_TLS_INFORMATION ThreadData[1];                                      // 0x010 0x010
} PROCESS_TLS_INFORMATION, *PPROCESS_TLS_INFORMATION;
```
