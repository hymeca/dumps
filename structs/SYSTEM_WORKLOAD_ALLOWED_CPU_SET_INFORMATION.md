# SYSTEM_WORKLOAD_ALLOWED_CPU_SET_INFORMATION

```C
typedef struct _SYSTEM_WORKLOAD_ALLOWED_CPU_SET_INFORMATION { // same size in both x86 and x64
   ULONGLONG WorkloadClass;                                                   // 0x000 0x000
   ULONGLONG CpuSets[1];                                                      // 0x008 0x008
} SYSTEM_WORKLOAD_ALLOWED_CPU_SET_INFORMATION, *PSYSTEM_WORKLOAD_ALLOWED_CPU_SET_INFORMATION;
```
