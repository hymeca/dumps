# SYSTEM_HANDLE_INFORMATION

```C
typedef struct _SYSTEM_HANDLE_INFORMATION { // x86 = 20, x64 = 32
   ULONG                          NumberOfHandles;           // 0x000 0x000
   SYSTEM_HANDLE_TABLE_ENTRY_INFO Handles[1];                // 0x004 0x008
} SYSTEM_HANDLE_INFORMATION, *PSYSTEM_HANDLE_INFORMATION;
```
