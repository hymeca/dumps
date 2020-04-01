# SYSTEM_PAGEFILE_INFORMATION

```C
typedef struct _SYSTEM_PAGEFILE_INFORMATION { // x86 = 24, x64 = 32
   ULONG          NextEntryOffset;                             // 0x000 0x000
   ULONG          TotalSize;                                   // 0x004 0x004
   ULONG          TotalInUse;                                  // 0x008 0x008
   ULONG          PeakUsage;                                   // 0x00c 0x00c
   UNICODE_STRING PageFileName;                                // 0x010 0x010
} SYSTEM_PAGEFILE_INFORMATION, *PSYSTEM_PAGEFILE_INFORMATION;
```
