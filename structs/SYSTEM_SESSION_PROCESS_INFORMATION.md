# SYSTEM_SESSION_PROCESS_INFORMATION

```C
typedef struct _SYSTEM_SESSION_PROCESS_INFORMATION { // x86 = 12, x64 = 16
   ULONG SessionId;                                                   // 0x000 0x000
   ULONG SizeOfBuf;                                                   // 0x004 0x004
   PVOID Buffer;                                                      // 0x008 0x008
} SYSTEM_SESSION_PROCESS_INFORMATION, *PSYSTEM_SESSION_PROCESS_INFORMATION;
```
