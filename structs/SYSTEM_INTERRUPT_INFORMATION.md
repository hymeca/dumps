# SYSTEM_INTERRUPT_INFORMATION

```C
typedef struct _SYSTEM_INTERRUPT_INFORMATION { // same size in both x86 and x64
   ULONG ContextSwitches;                                                     // 0x000 0x000
   ULONG DpcCount;                                                            // 0x004 0x004
   ULONG DpcRate;                                                             // 0x008 0x008
   ULONG TimeIncrement;                                                       // 0x00c 0x00c
   ULONG DpcBypassCount;                                                      // 0x010 0x010
   ULONG ApcBypassCount;                                                      // 0x014 0x014
} SYSTEM_INTERRUPT_INFORMATION, *PSYSTEM_INTERRUPT_INFORMATION;
```
