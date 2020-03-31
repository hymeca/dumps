# SYSTEM_HANDLE_TABLE_ENTRY_INFO_EX

```C
typedef struct _SYSTEM_HANDLE_TABLE_ENTRY_INFO_EX { // x86 = 28, x64 = 40
   PVOID     Object;                                                 // 0x000 0x000
   ULONG_PTR UniqueProcessId;                                        // 0x004 0x008
   ULONG_PTR HandleValue;                                            // 0x008 0x010
   ULONG     GrantedAccess;                                          // 0x00c 0x018
   USHORT    CreatorBackTraceIndex;                                  // 0x010 0x01c
   USHORT    ObjectTypeIndex;                                        // 0x012 0x01e
   ULONG     HandleAttributes;                                       // 0x014 0x020
   ULONG     Reserved;                                               // 0x018 0x024
} SYSTEM_HANDLE_TABLE_ENTRY_INFO_EX, *PSYSTEM_HANDLE_TABLE_ENTRY_INFO_EX;
```
