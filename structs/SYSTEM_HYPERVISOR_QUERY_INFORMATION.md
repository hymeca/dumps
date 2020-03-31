# SYSTEM_HYPERVISOR_QUERY_INFORMATION

```C
typedef struct _SYSTEM_HYPERVISOR_QUERY_INFORMATION { // same size in both x86 and x64
   BOOLEAN   HypervisorConnected;                                             // 0x000 0x000
   BOOLEAN   HypervisorDebuggingEnabled;                                      // 0x001 0x001
   BOOLEAN   HypervisorPresent;                                               // 0x002 0x002
   BYTE      HypervisorSchedulerType;                                         // 0x003 0x003
   BYTE      Spare0[4];                                                       // 0x004 0x004
   ULONGLONG EnabledEnlightenments;                                           // 0x008 0x008
} SYSTEM_HYPERVISOR_QUERY_INFORMATION, *PSYSTEM_HYPERVISOR_QUERY_INFORMATION;
```
