# SYSTEM_HANDLE_INFORMATION_EX

```C
typedef struct _SYSTEM_HANDLE_INFORMATION_EX { // x86 = 36, x64 = 56
   ULONG_PTR                         NumberOfHandles;           // 0x000 0x000
   ULONG_PTR                         Reserved;                  // 0x004 0x008
   SYSTEM_HANDLE_TABLE_ENTRY_INFO_EX Handles[1];                // 0x008 0x010
} SYSTEM_HANDLE_INFORMATION_EX, *PSYSTEM_HANDLE_INFORMATION_EX;
```
