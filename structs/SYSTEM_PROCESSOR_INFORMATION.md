# SYSTEM_PROCESSOR_INFORMATION

```C
typedef struct _SYSTEM_PROCESSOR_INFORMATION { // same size in both x86 and x64
   USHORT ProcessorArchitecture;                          // 0x000 0x000
   USHORT ProcessorLevel;                                 // 0x002 0x002
   USHORT ProcessorRevision;                              // 0x004 0x004
   USHORT MaximumProcessors;                              // 0x006 0x006
   ULONG  ProcessorFeatureBits;                           // 0x008 0x008
} SYSTEM_PROCESSOR_INFORMATION, *PSYSTEM_PROCESSOR_INFORMATION;
```
