# PROCESS_DISK_COUNTERS

```C
typedef struct _PROCESS_DISK_COUNTERS { // same size in both x86 and x64
   ULONGLONG BytesRead;                                      // 0x000 0x000
   ULONGLONG BytesWritten;                                   // 0x008 0x008
   ULONGLONG ReadOperationCount;                             // 0x010 0x010
   ULONGLONG WriteOperationCount;                            // 0x018 0x018
   ULONGLONG FlushOperationCount;                            // 0x020 0x020
} PROCESS_DISK_COUNTERS, *PPROCESS_DISK_COUNTERS;
```
