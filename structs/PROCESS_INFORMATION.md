# PROCESS_INFORMATION

```C
typedef struct _PROCESS_INFORMATION { // x86 = 16, x64 = 24
   HANDLE hProcess;                                    // 0x000 0x000
   HANDLE hThread;                                     // 0x004 0x008
   DWORD  dwProcessId;                                 // 0x008 0x010
   DWORD  dwThreadId;                                  // 0x00c 0x014
} PROCESS_INFORMATION, *LPPROCESS_INFORMATION, *PPROCESS_INFORMATION;
```
