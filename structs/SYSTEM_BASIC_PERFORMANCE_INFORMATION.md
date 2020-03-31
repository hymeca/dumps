# SYSTEM_BASIC_PERFORMANCE_INFORMATION

```C
typedef struct _SYSTEM_BASIC_PERFORMANCE_INFORMATION { // x86 = 16, x64 = 32
   SIZE_T AvailablePages;                                               // 0x000 0x000
   SIZE_T CommittedPages;                                               // 0x004 0x008
   SIZE_T CommitLimit;                                                  // 0x008 0x010
   SIZE_T PeakCommitment;                                               // 0x00c 0x018
} SYSTEM_BASIC_PERFORMANCE_INFORMATION, *PSYSTEM_BASIC_PERFORMANCE_INFORMATION;
```
