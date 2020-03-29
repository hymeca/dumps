# PROCESS_HANDLE_TABLE_ENTRY_INFO

```C
typedef struct _PROCESS_HANDLE_TABLE_ENTRY_INFO { // x86 = 28, x64 = 40
   HANDLE    HandleValue;                                          // 0x000 0x000
   ULONG_PTR HandleCount;                                          // 0x004 0x008
   ULONG_PTR PointerCount;                                         // 0x008 0x010
   ULONG     GrantedAccess;                                        // 0x00c 0x018
   ULONG     ObjectTypeIndex;                                      // 0x010 0x01c
   ULONG     HandleAttributes;                                     // 0x014 0x020
   ULONG     Reserved;                                             // 0x018 0x024
} PROCESS_HANDLE_TABLE_ENTRY_INFO, *PPROCESS_HANDLE_TABLE_ENTRY_INFO;
```
