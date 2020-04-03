# SYSTEM_THREAD_INFORMATION

```C
typedef struct _SYSTEM_THREAD_INFORMATION { // x86 = 64, x64 = 80
   LARGE_INTEGER KernelTime;                                 // 0x000 0x000
   LARGE_INTEGER UserTime;                                   // 0x008 0x008
   LARGE_INTEGER CreateTime;                                 // 0x010 0x010
   ULONG         WaitTime;                                   // 0x018 0x018
   PVOID         StartAddress;                               // 0x01c 0x020
   CLIENT_ID     ClientId;                                   // 0x020 0x028
   KPRIORITY     Priority;                                   // 0x028 0x038
   KPRIORITY     BasePriority;                               // 0x02c 0x03c
   ULONG         ContextSwitches;                            // 0x030 0x040
   ULONG         ThreadState;                                // 0x034 0x044
   ULONG         WaitReason;                                 // 0x038 0x048
} SYSTEM_THREAD_INFORMATION, *PSYSTEM_THREAD_INFORMATION;
```
