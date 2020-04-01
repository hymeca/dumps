# SYSTEM_OBJECT_INFORMATION

```C
typedef struct _SYSTEM_OBJECT_INFORMATION { // x86 = 48, x64 = 80
   ULONG                   NextEntryOffset;                         // 0x000 0x000
   PVOID                   Object;                                  // 0x004 0x008
   HANDLE                  CreatorUniqueProcess;                    // 0x008 0x010
   USHORT                  CreatorBackTraceIndex;                   // 0x00c 0x018
   USHORT                  Flags;                                   // 0x00e 0x01a
   LONG                    PointerCount;                            // 0x010 0x01c
   LONG                    HandleCount;                             // 0x014 0x020
   ULONG                   PagedPoolCharge;                         // 0x018 0x024
   ULONG                   NonPagedPoolCharge;                      // 0x01c 0x028
   HANDLE                  ExclusiveProcessId;                      // 0x020 0x030
   PVOID                   SecurityDescriptor;                      // 0x024 0x038
   OBJECT_NAME_INFORMATION NameInfo;                                // 0x028 0x040
} SYSTEM_OBJECT_INFORMATION, *PSYSTEM_OBJECT_INFORMATION;
```
