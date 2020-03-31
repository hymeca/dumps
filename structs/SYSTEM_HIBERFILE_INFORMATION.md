# SYSTEM_HIBERFILE_INFORMATION

```C
typedef struct _SYSTEM_HIBERFILE_INFORMATION { // same size in both x86 and x64
   ULONG         NumberOfMcbPairs;                                          // 0x000 0x000
   LARGE_INTEGER Mcb[1];                                                    // 0x008 0x008
} SYSTEM_HIBERFILE_INFORMATION, *PSYSTEM_HIBERFILE_INFORMATION;
```
