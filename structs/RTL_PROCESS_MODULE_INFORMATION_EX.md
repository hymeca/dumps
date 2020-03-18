# RTL_PROCESS_MODULE_INFORMATION_EX

```C
typedef struct _RTL_PROCESS_MODULE_INFORMATION_EX { // x86 = 300, x64 = 320
   ULONG                          NextOffset;                             // 0x000 0x000 (but Uint2B in pdb)
   RTL_PROCESS_MODULE_INFORMATION BaseInfo;                               // 0x004 0x008
   ULONG                          ImageChecksum;                          // 0x120 0x130
   ULONG                          TimeDateStamp;                          // 0x124 0x134
   PVOID                          DefaultBase;                            // 0x128 0x138
} RTL_PROCESS_MODULE_INFORMATION_EX, *PRTL_PROCESS_MODULE_INFORMATION_EX;
```
