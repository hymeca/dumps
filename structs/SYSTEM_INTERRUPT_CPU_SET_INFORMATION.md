# SYSTEM_INTERRUPT_CPU_SET_INFORMATION

```C
typedef struct _SYSTEM_INTERRUPT_CPU_SET_INFORMATION { // same size in both x86 and x64
   ULONG     Gsiv;                                                            // 0x000 0x000
   USHORT    Group;                                                           // 0x004 0x004
   ULONGLONG CpuSets;                                                         // 0x008 0x008
} SYSTEM_INTERRUPT_CPU_SET_INFORMATION, *PSYSTEM_INTERRUPT_CPU_SET_INFORMATION;
```
