# PROCESS_JOB_MEMORY_INFO

```C
typedef struct _PROCESS_JOB_MEMORY_INFO { // same size in both x86 and x64
   ULONGLONG SharedCommitUsage;                                               // 0x000 0x000
   ULONGLONG PrivateCommitUsage;                                              // 0x008 0x008
   ULONGLONG PeakPrivateCommitUsage;                                          // 0x010 0x010
   ULONGLONG PrivateCommitLimit;                                              // 0x018 0x018
   ULONGLONG TotalCommitLimit;                                                // 0x020 0x020
} PROCESS_JOB_MEMORY_INFO, *PPROCESS_JOB_MEMORY_INFO;
```
