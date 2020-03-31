# SYSTEM_HANDLE_TABLE_ENTRY_INFO

```C
typedef struct _SYSTEM_HANDLE_TABLE_ENTRY_INFO { // x86 = 16, x64 = 24
   USHORT UniqueProcessId;                                        // 0x000 0x000
   USHORT CreatorBackTraceIndex;                                  // 0x002 0x002
   UCHAR  ObjectTypeIndex;                                        // 0x004 0x004
   UCHAR  HandleAttributes;                                       // 0x005 0x005
   USHORT HandleValue;                                            // 0x006 0x006
   PVOID  Object;                                                 // 0x008 0x008
   ULONG  GrantedAccess;                                          // 0x00c 0x010
} SYSTEM_HANDLE_TABLE_ENTRY_INFO, *PSYSTEM_HANDLE_TABLE_ENTRY_INFO;
```
