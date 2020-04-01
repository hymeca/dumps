# SYSTEM_OBJECTTYPE_INFORMATION

```C
typedef struct _SYSTEM_OBJECTTYPE_INFORMATION { // x86 = 56, x64 = 64
   ULONG           NextEntryOffset;                              // 0x000 0x000
   ULONG           NumberOfObjects;                              // 0x004 0x004
   ULONG           NumberOfHandles;                              // 0x008 0x008
   ULONG           TypeIndex;                                    // 0x00c 0x00c
   ULONG           InvalidAttributes;                            // 0x010 0x010
   GENERIC_MAPPING GenericMapping;                               // 0x014 0x014
   ULONG           ValidAccessMask;                              // 0x024 0x024
   ULONG           PoolType;                                     // 0x028 0x028
   BOOLEAN         SecurityRequired;                             // 0x02c 0x02c
   BOOLEAN         WaitableObject;                               // 0x02d 0x02d
   UNICODE_STRING  TypeName;                                     // 0x030 0x030
} SYSTEM_OBJECTTYPE_INFORMATION, *PSYSTEM_OBJECTTYPE_INFORMATION;
```
