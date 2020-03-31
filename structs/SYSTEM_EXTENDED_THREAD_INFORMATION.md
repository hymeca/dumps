# SYSTEM_EXTENDED_THREAD_INFORMATION

```C
typedef struct _SYSTEM_EXTENDED_THREAD_INFORMATION { // x86 = 96, x64 = 136
   SYSTEM_THREAD_INFORMATION ThreadInfo;                              // 0x000 0x000
   PVOID                     StackBase;                               // 0x040 0x050
   PVOID                     StackLimit;                              // 0x044 0x058
   PVOID                     Win32StartAddress;                       // 0x048 0x060
   PTEB                      TebBase;                                 // 0x04c 0x068
   ULONG_PTR                 Reserved2;                               // 0x050 0x070
   ULONG_PTR                 Reserved3;                               // 0x054 0x078
   ULONG_PTR                 Reserved4;                               // 0x058 0x080
} SYSTEM_EXTENDED_THREAD_INFORMATION, *PSYSTEM_EXTENDED_THREAD_INFORMATION;
```
