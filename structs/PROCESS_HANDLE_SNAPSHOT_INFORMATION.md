# PROCESS_HANDLE_SNAPSHOT_INFORMATION

```C
typedef struct _PROCESS_HANDLE_SNAPSHOT_INFORMATION { // x86 = 36, x64 = 56
   ULONG_PTR                       NumberOfHandles;                           // 0x000 0x000
   ULONG_PTR                       Reserved;                                  // 0x004 0x008
   PROCESS_HANDLE_TABLE_ENTRY_INFO Handles[1];                                // 0x008 0x010
} PROCESS_HANDLE_SNAPSHOT_INFORMATION, *PPROCESS_HANDLE_SNAPSHOT_INFORMATION;
```
