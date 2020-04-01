# SYSTEM_LOOKASIDE_INFORMATION

```C
typedef struct _SYSTEM_LOOKASIDE_INFORMATION { // same size in both x86 and x64
   USHORT CurrentDepth;                                                       // 0x000 0x000
   USHORT MaximumDepth;                                                       // 0x002 0x002
   ULONG  TotalAllocates;                                                     // 0x004 0x004
   ULONG  AllocateMisses;                                                     // 0x008 0x008
   ULONG  TotalFrees;                                                         // 0x00c 0x00c
   ULONG  FreeMisses;                                                         // 0x010 0x010
   ULONG  Type;                                                               // 0x014 0x014
   ULONG  Tag;                                                                // 0x018 0x018
   ULONG  Size;                                                               // 0x01c 0x01c
} SYSTEM_LOOKASIDE_INFORMATION, *PSYSTEM_LOOKASIDE_INFORMATION;
```
