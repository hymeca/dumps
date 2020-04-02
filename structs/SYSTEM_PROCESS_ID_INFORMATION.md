# SYSTEM_PROCESS_ID_INFORMATION

```C
typedef struct _SYSTEM_PROCESS_ID_INFORMATION { // x86 = 12, x64 = 24
   HANDLE         ProcessId;                                     // 0x000 0x000
   UNICODE_STRING ImageName;                                     // 0x004 0x008
} SYSTEM_PROCESS_ID_INFORMATION, *PSYSTEM_PROCESS_ID_INFORMATION;
```
