# SYSTEM_VA_LIST_INFORMATION

```C
typedef struct _SYSTEM_VA_LIST_INFORMATION { // x86 = 16, x64 = 32
   SIZE_T VirtualSize;                                        // 0x000 0x000
   SIZE_T VirtualPeak;                                        // 0x004 0x008
   SIZE_T VirtualLimit;                                       // 0x008 0x010
   SIZE_T AllocationFailures;                                 // 0x00c 0x018
} SYSTEM_VA_LIST_INFORMATION, *PSYSTEM_VA_LIST_INFORMATION;
```
