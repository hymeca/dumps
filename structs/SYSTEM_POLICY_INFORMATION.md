# SYSTEM_POLICY_INFORMATION

```C
typedef struct _SYSTEM_POLICY_INFORMATION { // x86 = 20, x64 = 32
   PVOID InputData;                                                           // 0x000 0x000
   PVOID OutputData;                                                          // 0x004 0x008
   ULONG InputDataSize;                                                       // 0x008 0x010
   ULONG OutputDataSize;                                                      // 0x00c 0x014
   ULONG Version;                                                             // 0x010 0x018
} SYSTEM_POLICY_INFORMATION, *PSYSTEM_POLICY_INFORMATION;
```
