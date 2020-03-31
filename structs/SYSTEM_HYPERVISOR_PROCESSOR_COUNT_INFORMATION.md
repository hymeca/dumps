# SYSTEM_HYPERVISOR_PROCESSOR_COUNT_INFORMATION

```C
typedef struct _SYSTEM_HYPERVISOR_PROCESSOR_COUNT_INFORMATION { // same size in both x86 and x64
   ULONG NumberOfLogicalProcessors;                                           // 0x000 0x000
   ULONG NumberOfCores;                                                       // 0x004 0x004
} SYSTEM_HYPERVISOR_PROCESSOR_COUNT_INFORMATION, *PSYSTEM_HYPERVISOR_PROCESSOR_COUNT_INFORMATION;
```
