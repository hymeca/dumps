# SYSTEM_CPU_SET_TAG_INFORMATION

```C
typedef struct _SYSTEM_CPU_SET_TAG_INFORMATION { // same size in both x86 and x64
   ULONGLONG Tag;                                                             // 0x000 0x000
   ULONGLONG CpuSets[1];                                                      // 0x008 0x008
} SYSTEM_CPU_SET_TAG_INFORMATION, *PSYSTEM_CPU_SET_TAG_INFORMATION;
```
