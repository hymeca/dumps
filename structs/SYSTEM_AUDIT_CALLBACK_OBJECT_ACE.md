# SYSTEM_AUDIT_CALLBACK_OBJECT_ACE

```C
typedef struct _SYSTEM_AUDIT_CALLBACK_OBJECT_ACE { // same size in both x86 and x64
   ACE_HEADER Header;                                                         // 0x000 0x000
   ULONG      Mask;                                                           // 0x004 0x004
   ULONG      Flags;                                                          // 0x008 0x008
   GUID       ObjectType;                                                     // 0x00c 0x00c
   GUID       InheritedObjectType;                                            // 0x01c 0x01c
   ULONG      SidStart;                                                       // 0x02c 0x02c
} SYSTEM_AUDIT_CALLBACK_OBJECT_ACE, *PSYSTEM_AUDIT_CALLBACK_OBJECT_ACE;
```
