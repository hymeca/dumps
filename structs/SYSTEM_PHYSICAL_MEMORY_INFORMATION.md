# SYSTEM_PHYSICAL_MEMORY_INFORMATION

```C
typedef struct _SYSTEM_PHYSICAL_MEMORY_INFORMATION { // same size in both x86 and x64
   ULONGLONG TotalPhysicalBytes;                                              // 0x000 0x000
   ULONGLONG LowestPhysicalAddress;                                           // 0x008 0x008
   ULONGLONG HighestPhysicalAddress;                                          // 0x010 0x010
} SYSTEM_PHYSICAL_MEMORY_INFORMATION, *PSYSTEM_PHYSICAL_MEMORY_INFORMATION;
```
